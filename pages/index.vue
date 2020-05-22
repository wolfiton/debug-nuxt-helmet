<template>
  <div class="card w-3/4 mx-auto">
    <HeroSection />
  </div>
</template>

<script>
import HeroSection from '@/components/HeroSection.vue'
export default {
  components: {
    HeroSection
  },
  data() {
    return {
      content: 'Here I am'
    }
  }
}
</script>

<style></style>
