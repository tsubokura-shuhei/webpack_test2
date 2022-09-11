<template>
  <p class="msg-style">{{ message }}</p>
</template>

<script>
export default {
  data: () => {
    console.log('Vuejs is installed!');
    return{
      message:'Hey, this is Vue!',
    };
  },
};
</script>

<style>
.msg-style{
  color: green;
}
</style>