<template>
  <div id="app">
    <div id="nav">
      <nuxt-link to="/">
        Home
      </nuxt-link>|
      <nuxt-link to="/about">
        About
      </nuxt-link>
    </div>
    <nuxt />
  </div>
</template>

<style lang="scss">
@import '../assets/scss/styles.scss';
</style>

<script>
export default {
  data () {
    return {
      title: 'Our App'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        { hid: 'description', name: 'description', content: 'Our remarkable project' }
      ]
    }
  }
}
</script>
