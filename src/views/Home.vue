<template>
  <div class="home container md:mx-auto px-4">

    <h1 class="text-3xl text-center p-2 font-bold">
      Todo App
    </h1>
    <div>
      <NewItem />
      <TodoList />
    </div>
  </div>
</template>

<script lang="ts">
import NewItem from '@/components/NewItem.vue';
import TodoList from '@/components/TodoList.vue';

import { defineComponent } from 'vue'
export default defineComponent({
  components: { NewItem, TodoList },
})
</script>
