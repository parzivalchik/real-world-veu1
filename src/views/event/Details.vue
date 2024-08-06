<script setup>

const props = defineProps(["event"]);

</script>

<template>
    <p>Duration: {{ event.time }} Released: {{ event.date }} Watch on: {{ event.location }}</p>
    <p>{{ event.description }}</p>
</template>