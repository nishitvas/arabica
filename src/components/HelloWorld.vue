<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      An awesome website is being built using <a href="https://vuejs.org" target="_blank" rel="noopener">Vue.js</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}
</style>
