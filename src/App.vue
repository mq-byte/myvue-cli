<template>
  <div id="app">
    HelloWorld
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  created () {
      console.log('App');
  }
}
</script>

<style>
#app{
    background: red;
}
</style>
