<script setup >
import {ref} from 'vue';
const count = ref(0);
</script>

<template>
 

  <main>
    <div class="div1">
      <h4>
        The conunter app..
      </h4>
      <h1>
        {{ count }}
      </h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>

<style scoped>
body{
  width: 100%;
  height:100vh;
}
  main{
    margin: auto;
    width: 50%;
    background-color: aquamarine;
    padding-bottom: 20px;
    border: 3px solid red;
    display: flex;
    align-items:center;
    justify-content: center;
   
  }

  .div1{
    text-align: center;
  }
</style>
