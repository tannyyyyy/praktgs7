<template>
  <ToDoList />
</template>

<script>
import ToDoList from "./components/TodoList.vue";

export default {
  name: "App",

  components: {
    ToDoList,
  },
};
</script>

<style>
body {
  background-image: url(../public/cb.jpeg);
  background: cover;
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
