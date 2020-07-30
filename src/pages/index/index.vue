<template>
  <div class="home">
    <!-- 背景图片 -->
    <img :src="img.homeBg" alt="" class="home-bg">

    <!-- 搜索框 -->
    <div class="home-search">
      <div></div>
    </div>
  </div>
</template>

<script>
import img from '@/utils/img'

export default {
  data () {
    return {
      img
    }
  }
}
</script>

<style scoped>
.home-bg{
  width: 100%;
  height: 530rpx;
}
</style>
