<script setup lang="ts">
import Mock from 'mockjs'
import AButton from '@/components/AButton.vue'
</script>

<template>
  {{ Mock.mock('@cname') }}
  <AButton />
</template>
