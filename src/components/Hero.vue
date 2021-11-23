<template>
    <div>
    </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    div {
        height: 400px;
        background-image: url('../assets/bg-hero.jpg');
        background-size: contain;
        background-position: top;
        background-repeat: no-repeat;
    }
</style>