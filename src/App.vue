<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorldTwo msg="管理番号/照片" />
  </div>
</template>

<script>
import HelloWorldTwo from "./components/HelloWorldTwo.vue";
export default {
  name: "App",
  components: {
    HelloWorldTwo,
  },
};
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
