<template>
  <div class="hello">
    <div>{{ msg }}</div>
    <Childs></Childs>
  </div>
</template>

<script>
import Childs from "./child";
export default {
  name: 'HelloWorld',
  components:{
    Childs
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  font-size: 30px;
}
.asd{
  border: 1px solid #000;
}
</style>
