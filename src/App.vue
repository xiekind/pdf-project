<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
      
    </div>-->
    <!-- <HomePage></HomePage>
    <AboutPage></AboutPage> -->
    <v-main>
      <router-view/>
    </v-main>
  </div>
</template>

<script>
// import HomePage from "./views/Home.vue";
// import AboutPage from "@/views/About.vue";
export default {
  name: "Apps",
  components: {
    // HomePage,
    // AboutPage
  }
};
</script>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
