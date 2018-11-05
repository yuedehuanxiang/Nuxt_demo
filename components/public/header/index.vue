<template>
  <el-row
    :gutter="15"
    class="m-header">
    <el-col :span="6">
      <geo/>
    </el-col>
    <el-col :span="6">
      1
    </el-col>
    <el-col :span="6">
      2
    </el-col>
    <el-col :span="6">
      3
    </el-col>
  </el-row>
</template>

<script>
  import Geo from './geo'
    export default {
        name: "Index",
      components: {
          Geo
      }
    }
</script>

<style lang="scss">
  @import "@/assets/css/public/layout.scss";
</style>
