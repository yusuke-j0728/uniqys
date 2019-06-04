<template>
  <div id="app">
    <input type="text" v-model="input">
    <button>submit</button>
    <p>{{ input }}</p>
  </div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      input: ''
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
