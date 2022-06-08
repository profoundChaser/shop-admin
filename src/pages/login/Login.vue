<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div>
    <input type="text" />
    <input type="password" />
    <button>登录</button>
    <button class="upload" ref="upload">文件上传</button>
    <input type="file" multiple />
  </div>
</template>

<style lang="scss" scoped></style>
