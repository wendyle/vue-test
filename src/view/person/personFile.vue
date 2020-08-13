<template>
  <div class="person-file" :style="{backgroundImage:'url('+src+')'}">
    <svg id="relation-chart"></svg>
  </div>
</template>

<script>
export default {
  name: 'personFile',
  data() {
    return {
      src: require('@/assets/common/bg.png')
    }
  }
}
</script>

<style lang="scss" scoped>
.person-file {
  position: relative;
  width:100%;
  height:100%;
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
</style>
