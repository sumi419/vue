<template>
  <div>
    <h1>Events Listing</h1>
    <EventCard/>
    <router-link :to="{ name: 'event-show', params: {id: '1'} }">Show Event #1</router-link>
  </div>
</template>

import EventCard from '@/components/EventCard.vue'
<script>
export default {
  components: {
    EventCard
  }
}
</script>

<style>
</style>
