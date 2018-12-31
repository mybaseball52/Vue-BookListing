<template>
    <li>{{book.title}}:{{book.author}}</li>
</template>

<script>
export default {
  name: 'BookItem',
  data() {
    return {
      props: 'book',
    };
  },
};
</script>

<style>
</style>