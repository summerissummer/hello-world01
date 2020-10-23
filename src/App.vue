<template>
  <div id="app">
    <h2>预祝大家前程似锦</h2>
    <img src="../../dist/static/images/1.jepg"/><br/>
        <img src="../../dist/static/images/2.jepg"/><br/>
        <img src="../../dist/static/images/3.jpg"/><br/>
        <img src="../../dist/static/images/4.jpg"/><br/>
        <img src="../../dist/static/images/5.jpg"/><br/>
        <img src="../../dist/static/images/6.jpg"/><br/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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
