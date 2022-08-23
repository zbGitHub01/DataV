<template>
  <div id="app">
      <!-- <dv-full-screen-container>content</dv-full-screen-container> -->
    <DataV/>
  </div>
</template>

<script>
import DataV from './components/datav';

export default {
  name: 'App',
  components: {
    DataV,
  },
  data(){
    return {
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
