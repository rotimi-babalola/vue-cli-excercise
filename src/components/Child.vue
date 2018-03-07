<template>
    <div class="place">
        <img :src="image" width="235" height="300" />
        <h2>{{ name }}</h2>
        <p>{{ description }}</p>
    </div>
</template>

<script>
export default {
  props: ['image', 'description', 'name'],
};
</script>

<style scoped>

</style>
