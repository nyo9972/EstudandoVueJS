<template>

<div> 

<h1>Testando componentes VUE</h1>
<jabiru></jabiru>
<labiru></labiru>

</div>
  
</template>

<script>

import jabiru from './intro.vue'
import labiru from './under.vue'

export default {
  components:{
    jabiru,
    labiru
  }
  
}
</script>

<style scoped>
h1{
  font-size: 50px;
  font-weight:bold;
  color: red;
}

</style>
