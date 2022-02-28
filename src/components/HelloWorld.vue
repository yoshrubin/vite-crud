<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <div id="app">
    <p>You clicked {{ count }} times</p>
    <button @click="count++">Click me</button>
  </div>
</template>

<style scoped>
</style>
