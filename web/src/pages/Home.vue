<template>
    <ProjectOverview/>
</template>

<script>
import ProjectOverview from '@/components/ProjectOverview.vue'

export default {
  name: 'home',
  components: {
    ProjectOverview
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
