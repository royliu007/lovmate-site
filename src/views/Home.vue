<template>
  <div class="home">
    <l-header></l-header>abc
    <l-footer></l-footer>
  </div>
</template>

<script>
import LHeader from '../common/header.vue'
import LFooter from '../common/footer.vue'

export default {
  name: 'home',
  components: {
    LHeader,
    LFooter
  }
}
</script>
