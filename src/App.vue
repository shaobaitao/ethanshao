<template>
    <v-app id="app">
        <HelloWorld />
    </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: {
        HelloWorld
    }
}
</script>

<style>
#app {
    font-family: quickSand, serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

* {
    padding: 0;
    margin: 0;
}
::-webkit-scrollbar {
    width: 0 !important;
}


</style>
