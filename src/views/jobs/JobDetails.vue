<template>
  <h1>The job id is {{ id }}</h1>
</template>

<script>
export default {
  props: ['id'],
  data() {
    return {
      // id: this.$route.params.id,
    }
  },
}
</script>
