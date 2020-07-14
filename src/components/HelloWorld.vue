<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Editor />
  </div>
</template>

<script>
import Editor from './Editor.vue'

export default {
  name: 'HelloWorld',
  components: {
    Editor
  },
  props: {
    msg: String
  }
}
</script>