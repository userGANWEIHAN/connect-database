<template>
  <span>
    <span>
      {{ listing.street }} {{ listing.street_nr }}, {{
        listing.city }}, for ${{ listing.price }}
    </span>
  </span>
</template>

<script setup>
defineProps({
  listing:Object,
})
</script>