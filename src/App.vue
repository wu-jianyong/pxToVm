<template>
  <div id="app">
    <img src="./assets/logo.png">
    <span>中国之星</span>
    <div class="one">1</div>
    <div class="two">2</div>
    <div class="three">3</div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
  span{
    font-size: 32px;
  }
  .one{
    width:750px;
    height:50px;
    background: #42b983;
  }
  .two{
    width:375px;
    height:50px;
    background: #000;
  }
  .three{
    width:187px;
    height:50px;
    background:yellowgreen;
  }
  html,body{
    padding: 0;
    margin: 0;
  }
</style>
