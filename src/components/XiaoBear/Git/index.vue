<template>
  <div>
    <svg-icon icon-class="github" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'XiaoBearGit',
  data() {
    return {
      url: 'https://javaxiaobear.cn'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
