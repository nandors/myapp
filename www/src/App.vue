<template>
  <div>
    <h1> {{ url }} </h1>
    <router-link to="/" tag="span" style="cursor: pointer">
      Home
    </router-link>
    <router-link to="/pag1" tag="span" style="cursor: pointer">
      Pagina 1
    </router-link>
    <router-link to="/pag2" tag="span" style="cursor: pointer">
      Pagina 1
    </router-link>

    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        url: window.location.href
      }
    }
  }
</script>

<style>

</style>
