<script setup>
import data from "./data/data";
</script>

<template>
  <h1 v-if="data.name == 'Towfik'">{{ data.name }}</h1>
</template>

<style scoped></style>
