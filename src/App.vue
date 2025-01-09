<template>
<div><h1>incrementation and decrementation</h1></div>
  <div>
    <button @click="handleIncrement">increment</button>
    <button>{{ count }}</button>
    <button @click="handleDecrement">decrement</button>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      count: 0, 
    };
  },
  methods: {
    handleIncrement() {
      this.count++; 
    },
    handleDecrement() {
      this.count--; 
    },
  },
};
</script>

<style>
button {
  font-family: Arial, sans-serif;
  color: blue;
  width: 15rem;
  height: 0%;
  margin-left: 450px;
  background-color: blue;
  color:white;
}
h1{
  margin-left:350px;
}
</style>
