<template>
  <button :class="btnClass">{{ btnText }}</button>
</template>

<script>
export default {
  name: "Button",
  props: {
    btnText: String,
    btnClass: String
  }
}
</script>

<style lang="css" scoped>
  button{
    width: 150px;
    height: 50px;
    background: #2c3e50;
    color: aliceblue;
    font-size: 24px;
    cursor: pointer;
  }
</style>
