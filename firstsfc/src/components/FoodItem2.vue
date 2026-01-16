<template>
  <div class="grapes">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Oranges and Grapes',
      message: 'I like oranges and Grapes'
    }
  }
};
</script>

<style>
    .grapes {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: purple;
  }
</style>