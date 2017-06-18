<template>
<div class="container">
    <img class="avatar" src="../images/avatar/1.png">
    <text class="motto">hello,{{username}}</text>
    <router-link class="journey-container" to="./posts/post">
        <span class="journey">开启小程序之旅</span>
    </router-link>
</div>
</template>
<script>
export default {
  data () {
    return {
      username: 'BR'
    }
  },
  methods: {}
}
</script>
<style scope="lang">
html, body{
    height: 100%;
}
.container{
    display: flex;
    flex-direction:column;
    align-items: center;
    background-color:#b3d4db;
}

.avatar{
    width:200px;
    height:200px;
    margin-top:160px;
}

.motto{
    margin-top:100px;
    font-size:32px;
    font-weight: bold;
}

.journey-container{
    margin-top: 200px;
    border: 1px solid #405f80;
    width: 200px;
    height: 80px;
    border-radius: 5px;
    text-align:center;
}

.journey{
    font-size:22px;
    font-weight: bold;
    line-height:80px;
    color: #405f80;
}
</style>
