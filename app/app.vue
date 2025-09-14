<template>
  <div class="demo-progress">
    <el-icon><Document /></el-icon>
    <h1>HELLO WORLD!</h1>
    <el-progress :text-inside="true" :stroke-width="26" :percentage="80" />
  </div>
</template>
<script setup>
import { Document } from "@element-plus/icons-vue"
</script>
<style lang="scss" scoped>
.demo-progress {
  .el-progress--line {
    margin-bottom: 15px;
    max-width: 600px;
  }
}
</style>
