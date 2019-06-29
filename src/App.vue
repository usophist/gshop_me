<template>
  <div id="app">
    <router-view/>
    <FooterGuide v-if="$route.meta.showFooter"/>
  </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide';
export default {
  components:{
    FooterGuide
  },
  name: 'App'
}
</script>

<style>

</style>
