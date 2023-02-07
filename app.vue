<template>
  <div>
    <button>Button</button>
    <pre>{{ data }} </pre>
  </div>
</template>

<style>
div {
  padding: 12rem 3rem;
}
</style>

<script setup>
// const { data } = await useFetch('/api/test');
const data = { tree: 'house' };
</script>
