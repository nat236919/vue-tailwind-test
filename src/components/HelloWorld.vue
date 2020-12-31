<template>
  <div class="hello flex justify-center">
    <h1 class="text-5xl text-white">{{ msg }}</h1>
    <p>Hello World</p>
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

</style>
