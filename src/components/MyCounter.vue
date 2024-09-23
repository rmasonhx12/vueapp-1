<script setup>
import { ref } from "vue";

// create reactive variable count with initial value = 0
const count = ref(0);

</script>

<template>
    <h1>My Counter Component</h1>
    Reactive variable count: <b>{{ count }}</b>
    <br/> <br/>
    <button @click="count++">count + 1</button>
</template>

<style scoped>
</style>