<!-- script内にJSコード記載 -->
<script setup lang="ts">
import { ref } from 'vue'

// refはテンプレートに表示させる変数を定義する
const name = ref('tester1')
</script>

<!-- templateにHTMLを記載 -->
<template>
  <div>
    <!-- マスタッシュ構文でrefで定義した変数を表示する -->
    <h1>{{ name }}</h1>
  </div>
</template>