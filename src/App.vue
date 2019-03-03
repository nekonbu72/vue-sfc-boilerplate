<template>
  <div>
    <HelloWorld msg="Hello"/>
    <h1>{{ greeting }}</h1>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  },
  data: function() {
    return {
      greeting: "World!"
    };
  }
};
</script>

<style scoped>
</style>
