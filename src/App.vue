<template>
  <img alt="demutenu logo" src="./assets/demulogo.png">
  <MiComponente msg="escribiendo sitios web, desarrollando historias"/>
</template>

<script>
import MiComponente from './components/MiComponente.vue'

export default {
  name: 'App',
  components: {
    MiComponente
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Alef&display=swap');

#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/
  font-family: 'Alef', sans-serif;
  text-align: center;
}
</style>
