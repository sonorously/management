<template>
  <aside class="nav-bread">


    <el-breadcrumb separator="/">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item><a href="/">活动管理</a></el-breadcrumb-item>
      <el-breadcrumb-item>活动列表</el-breadcrumb-item>
      <el-breadcrumb-item>活动详情</el-breadcrumb-item>
    </el-breadcrumb>
  </aside>

</template>

<script>
export default {
  name: "navBread"
}
</script>

<style scoped lang="scss">
.nav-bread{
  height: 30px;
  border-bottom: 1px solid #666666;
}
</style>