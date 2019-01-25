<template>
  <div id="app">
    <div id="cover"></div>
    <Header></Header>
    <todo></todo>
  </div>
</template>
<script>
import Header from './todo/header.vue';
import todo from './todo/todo.vue';
export default {
  data() {
    return {};
  },
  components: {
    Header,
    todo
  }
};
</script>

<style lang="less" scoped>
#app {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}
#cover {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background-color: #999;
  opacity: 0.9;
  z-index: -1;
}
</style>
