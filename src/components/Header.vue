<template>
  <header class="hello">
    <ul>
      <li>Home</li>
      <li>About us</li>
      <li>Services</li>
      <li>Contacts</li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  background-color: #2c3e50;
  color: #ffffff;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
