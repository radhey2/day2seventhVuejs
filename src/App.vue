<template>
 <div id="app">
  <ul>
    <li v-for="num in 5" :key="num">
      {{ num }}
    </li>
  </ul>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
