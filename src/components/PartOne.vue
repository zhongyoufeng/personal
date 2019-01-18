<template>
  <div class="part-one">
    <img class="part-one-image" :src="headImage" alt="头像">
   
    <p>姓&emsp;&emsp;名：钟优锋</p>
    <p>学&emsp;&emsp;历：大专</p>
    <p>工作年限：3 年</p>
    <p>年&emsp;&emsp;龄：24</p>
    <p>电话：15770652330</p>
    <p>邮箱：zhongyoufeng@126.com</p>
    <p>个人网站：<a href="www.mrzyf.clud" target="_blank">www.mrzyf.clud</a></p>
   
  </div>
</template>

<script>
export default {
  name: "partOne",
  data() {
    return {
      headImage: require('../assets/img/head_image.png')
    }
  }
};
</script>

<style scoped>
a {
  color: deepskyblue;
}
a:hover {
  color: rgb(118, 190, 248);
}
p {
  line-height: 30px;
}
.part-one {
  width: 100%;
  height: 500px;
  border: 40px solid transparent;
  border-image: url("~@/./assets/img/border_image.png") 30 30 stretch;
  background: #18202d;
  padding-left: 10px;
}
.part-one-image {
  width: 200px;
  height: 200px;
  margin-bottom: 10px;
}
</style>