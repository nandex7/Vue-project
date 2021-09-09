<template>
<div class="center">
  <p >  {{count}} </p>
  <button @click="addCount">add</button>
</div>  
</template>


<script>
  export default{
    data() {
      return {
        count:1
      };
    },
    methods: {
      addCount() {
        this.count++;

      }
          },
    

  };
</script>


<style>
.center {
  height:100vh;
  display:flex;
  align-items:center;
}
</style>
