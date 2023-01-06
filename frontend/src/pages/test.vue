<template>
  <row>
    <h1>Pinia入門</h1>
    <p>Count:{{ counter.count }}</p>
  </row>
</template>

<script setup>
import { useStoreCounter } from '../store/counter';
const counter = useStoreCounter();
</script>
