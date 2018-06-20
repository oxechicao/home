<template>
  <div id="app">
    <div class="content">
      <div class="profile-photo">
      </div>
      <div class="link-menu me"></div>
      <div class="link-menu projects"></div>
      <div class="link-menu blog"></div>
      <div class="link-menu nature-syntax-theme"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #100f11;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
  color: rgb(182, 219, 206);
}

.link-menu {
  width: 250px;
  height: 250px;
  text-align: right;
  align-self: flex-end;
  color: black;
  background: white;
}
</style>
