<template>
  <button @click="increment">Add 22</button>
</template>
<script>
import { mapActions } from 'vuex';

export default {
  methods: {
    // addOne() {
    //   this.$store.dispatch('increment');
    // }
    ...mapActions(['increment'])
  }
};
</script>
