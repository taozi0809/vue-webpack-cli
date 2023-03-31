<template>
  <div class="box">我是App哈哈哈哈 {{ url }}</div>
</template>

<script>
export default {
  data() {
    return {
      url: process.env.VUE_APP_URL,
    };
  },
  mounted(){
    const a = 1
  },
};
</script>

  <style lang="scss">
.box {
  width: 500px;
  height: 200px;
  color: #fff;
  background-color: #000;
  background: url(@/assets/images/guang.png);
}
</style>
