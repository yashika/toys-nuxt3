<template>
  <NuxtLink class="logo" to="/">
    <img src="@/assets/images/newlogo.png" alt="logo">
<!--    <span class="title">DNK Code</span>-->
  </NuxtLink>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'Logo'
});
</script>

<style scoped>
.logo {
  display: flex;
  align-items: center;
  margin-right: 44px;
}

.title {
  white-space: nowrap;
}

.logo img {
  height: 61px;
  width: auto;
}

.logo .title {
  margin-left: 20px;
  font-weight: bold;
  font-size: 25px;
  line-height: 30px;
  color: #fff;
}
</style>