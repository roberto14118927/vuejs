<template>
  <div id="app">
    <img src="https://roberto14118927.github.io/vuejs/src/assets/logo.png">
    <h1>{{ msg }}</h1>
    <h3>{{ msg1 }}</h3>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Prepárense para el Super Curso de Vue.js',
      msg1: 'Ing. Roberto Eduardo Guzmán Ruiz'
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

h1, h2 {
  font-weight: normal;
  color: #2c3e50  
}

h3 {
  font-weight: normal;
  color: #c1bdbd
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
