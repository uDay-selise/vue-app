<template>
  <div style="font-family: sans-serif; padding: 2rem">
    <h1>Studio Compatibility Test: Vue</h1>
    <p>This is a plain Vue app with no React in it at all. Studio should reject this import.</p>
    <button @click="count++">Clicked {{ count }} times</button>
  </div>
</template>

<script setup>
import { ref } from "vue";
const count = ref(0);
</script>
