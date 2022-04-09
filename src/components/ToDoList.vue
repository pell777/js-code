<template>
  <div>
    <ul>
        {{todos}}
      <ToDoItems/>
    </ul>
  </div>
</template>

<script>
import ToDoItems from "@/components/ToDoItems";
export default {
    props:['todos'],
  components: {
    ToDoItems
  },
};
</script>