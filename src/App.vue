<template>
  <div>
    <add-blog></add-blog>
  </div>
</template>

<script>
// Imports
import addBlog from "./components/addBlog.vue";

export default {
  components: {
    "add-blog": addBlog,
   
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap");
body {
  margin: 0;
  font-family: "Merriweather", serif;
  font-weight: 400;
  background: #ffffff;
}
</style>
