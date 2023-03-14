<script setup>
import { Head, Link } from '@inertiajs/vue3';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <Head title="About" />
        <nav class="navbar fixed-top bg-dark justify-content-center">
            <ul class="nav justify-content-center">
                <li class="nav-item active">
                    <a class="nav-link link-warning active" aria-current="page" href="/">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link link-warning" href="/about">-> About</a>
                </li>
                <li class="nav-item">
                    <img src="img/logo.svg " alt="YNV-logo"  width="45" height="45"/>
                </li>
                <li class="nav-item">
                    <a class="nav-link link-warning" href="/project">Project</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link link-warning" href="/contact">Contact</a>
                </li>
            </ul>
        </nav>
        <div class="containar-fluid d-flex align-items-center bg-gray-100 dark:bg-dots-lighter dark:bg-gray-900 selection:bg-  -500 selection:text-white">
            <div class="container text-center">
                <div class="row">
                    <div class="col-md-2 col-xs-12">
                        <br><br><br>
                        <img class="rounded float-end" src="img/logo.svg" alt="YNV-logo"  width="250" height="250"/>
                    </div>
                    <div class="col-md-10 col-xs-12">
                                        <h1 class="text-white text-center">
                                            About
                                        </h1>
                                        <p class="text-white">
                                            Bienvenido(a) a mi página "About". Soy un desarrollador de software con experiencia en la creación
                                            de soluciones de software innovadoras y eficientes para empresas y clientes individuales.
                                            Mi pasión por la programación comenzó cuando era joven, y desde entonces he estado desarrollando
                                            mis habilidades y experiencia en este campo. Me apasiona la tecnología y la forma en que puede 
                                            mejorar nuestras vidas cotidianas.

                                            Mi objetivo como desarrollador de software es crear soluciones que no solo resuelvan los problemas 
                                            del cliente, sino que también sean intuitivas, fáciles de usar y atractivas visualmente. Creo que 
                                            la usabilidad es tan importante como la funcionalidad y siempre trabajo para lograr un equilibrio entre ambas.

                                            En esta página "About", encontrarás más información sobre mí y mi experiencia en el campo del 
                                            desarrollo de software. Estoy emocionado de compartir mi trabajo contigo y espero que disfrutes 
                                            explorando mi portafolio y mi experiencia.

                                            ¡Gracias por visitar mi página "About"!
                                        </p>

                                        <p class="text-white">
                                            Bienvenido(a) a mi página "About". Soy un desarrollador de software con experiencia en la creación
                                            de soluciones de software innovadoras y eficientes para empresas y clientes individuales.
                                            Mi pasión por la programación comenzó cuando era joven, y desde entonces he estado desarrollando
                                            mis habilidades y experiencia en este campo. Me apasiona la tecnología y la forma en que puede 
                                            mejorar nuestras vidas cotidianas.

                                            Mi objetivo como desarrollador de software es crear soluciones que no solo resuelvan los problemas 
                                            del cliente, sino que también sean intuitivas, fáciles de usar y atractivas visualmente. Creo que 
                                            la usabilidad es tan importante como la funcionalidad y siempre trabajo para lograr un equilibrio entre ambas.

                                            En esta página "About", encontrarás más información sobre mí y mi experiencia en el campo del 
                                            desarrollo de software. Estoy emocionado de compartir mi trabajo contigo y espero que disfrutes 
                                            explorando mi portafolio y mi experiencia.

                                            ¡Gracias por visitar mi página "About"!
                                        </p>

                                        <p class="text-white">
                                            Bienvenido(a) a mi página "About". Soy un desarrollador de software con experiencia en la creación
                                            de soluciones de software innovadoras y eficientes para empresas y clientes individuales.
                                            Mi pasión por la programación comenzó cuando era joven, y desde entonces he estado desarrollando
                                            mis habilidades y experiencia en este campo. Me apasiona la tecnología y la forma en que puede 
                                            mejorar nuestras vidas cotidianas.

                                            Mi objetivo como desarrollador de software es crear soluciones que no solo resuelvan los problemas 
                                            del cliente, sino que también sean intuitivas, fáciles de usar y atractivas visualmente. Creo que 
                                            la usabilidad es tan importante como la funcionalidad y siempre trabajo para lograr un equilibrio entre ambas.

                                            En esta página "About", encontrarás más información sobre mí y mi experiencia en el campo del 
                                            desarrollo de software. Estoy emocionado de compartir mi trabajo contigo y espero que disfrutes 
                                            explorando mi portafolio y mi experiencia.

                                            ¡Gracias por visitar mi página "About"!
                                        </p>
                    </div>
                    <div class="col-md-12 col-xs-12">
                        <div class="container col-md-12 text-center text-white">
                            <div class="row">
                                <div class="col-md-6 col-xs-12">
                                    <p>Yovan Ram&oacute;n Yaune Enovore &copy; 2023</p>  
                                </div>
                                <div class="col-md-6 col-xs-12">                       
                                    Update: 22:20:40 - 13/13/2023
                                </div>
                                <hr>
                                <div class="col-md-6 col-xs-12">
                                    Licencia del c&oacute;digo MIT, docs <a ref="http://creativecommons.org/licenses/by-nc/4.0/"></a><a class="link-light" rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">CC BY 4.0</a> .
                                </div>
                                <div class="col-md-6 col-xs-12">
                                            <div class="container text-center">
                                                <div class="row align-items-start">
                                                <div class="col">
                                                    <a class="link-warning" href="https://github.com/ynvYauneEnovore">GitHub</a>
                                                </div>
                                                <div class="col">
                                                    <a class="link-warning" href="https://www.facebook.com/ynvyvn/">Facebook</a>
                                                </div>
                                                <div class="col">
                                                    <a class="link-warning" href="mailto:yovanuxf@gmail.com?Subject=system%esta-f%contact">Gmail</a>
                                                </div>
                                                <div class="col">
                                                    <a class="link-warning" href="https://www.instagram.com/ynvenovore/">Intagram</a>
                                                </div>
                                                <div class="col">
                                                    <a class="link-warning" href="https://www.linkedin.com/in/yovan-r-yaune-enovore-176817167/">Linkedin</a><br><br>
                                                </div>
                                                </div>
                                            </div>
                                </div>
                            </div>
                        </div>  
                    </div>
                    <br>
                </div>
            </div>
        </div>          
</template>

<style>
.bg-dots-darker {
    background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(0,0,0,0.07)'/%3E%3C/svg%3E");
}
@media (prefers-color-scheme: dark) {
    .dark\:bg-dots-lighter {
        background-image: url("data:image/svg+xml,%3Csvg width='30' height='30' viewBox='0 0 30 30' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1.22676 0C1.91374 0 2.45351 0.539773 2.45351 1.22676C2.45351 1.91374 1.91374 2.45351 1.22676 2.45351C0.539773 2.45351 0 1.91374 0 1.22676C0 0.539773 0.539773 0 1.22676 0Z' fill='rgba(255,255,255,0.07)'/%3E%3C/svg%3E");
    }
}
</style>