<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
}

.el-submenu [class^=fa] {
  vertical-align: baseline;
  margin-right: 6px;
  width: 23px;
  text-align: center;
}

.el-menu-item [class^=fa] {
  vertical-align: baseline;
  margin-right: 10px;
}
</style>
