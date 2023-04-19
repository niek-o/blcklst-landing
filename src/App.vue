<script setup lang="ts">

</script>

<template>
    <div class="parallax overflow-hidden md:overflow-y-visible">
        <img src="/img/bg.png" class="parallax-layer layer1 h-screen sm:h-full w-screen md:w-full sm:h-auto -z-10">
        <img src="/img/bg.png" class="parallax-layer layer1 mt-[140vh] lg:mt-[90vh] xl:mt-[30vh] md:w-full h-auto -z-10">

        <div class="hero z-10 parallax-layer layer1 mt-32 md:mt-64">
            <h1 class=" text-white text-xl font-bold text-center">EVATIA</h1>
            <h1 class=" text-white text-6xl md:text-9xl font-bold text-center">BLCKLST</h1>
        </div>

        <div class="hero z-10 parallax-layer layer1 mt-[30rem] md:mt-[150rem] flex w-full justify-center place-items-center">
            <a href="https://distrokid.com/hyperfollow/evatia/blcklst"
               class="p-3 text-white text-3xl font-bold text-center border-4 border-white">VIEW TRANSMISSION LOG</a>
        </div>

        <img src="/img/mako.png" class="parallax-layer layer2 w-64 h-auto -z-10">
        <img src="/img/planet.png" class="parallax-layer layer3 w-[100rem] h-auto right-96">
    </div>


</template>

<style scoped>
/* if you do not have this, you will see a
vertical scrollbar on the .parallax div */
.parallax {
    height: 100vh;
    overflow-x: hidden;

    perspective: 1px;
}

.parallax-layer {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
}

.layer1 {
    transform: translateZ(0);
}

.layer2 {
    top: 10rem;
    left: -10rem;
    transform: translateZ(-1px);
}

.layer3 {
    top: 40rem;
    left: 10rem;
    transform: translateZ(-2px);
}

@media (min-width: 640px) {
    .layer2 {
        top: 15rem;
    }

    .layer3 {
        top: 30rem;
        left: 50rem;
    }
}

@media (min-width: 768px) {
    .layer3 {
        top: 100rem;
        left: 60rem;
    }
}

@media (min-width: 1024px) {
    .layer3 {
        top: 90rem;
        left: 100rem;
    }
}

@media (min-width: 1280px) {
    .layer3 {
        top: 90rem;
        left: 120rem;
    }
}
</style>
