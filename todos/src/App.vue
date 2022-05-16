<template>
  <div class="app-container">
    <h1>app 根组件</h1>
  </div>
</template>

<script>
export default {
  name: 'MyApp',
  data () {
    return {
      // 定义任务列表的数据
      todolist: [
        { id: 1, task: '周一早上九点早起', done: false },
        { id: 2, task: '周一晚上八点吃早餐', done: false },
        { id: 3, task: '准备会议', done: true }
      ]
    }
  }
}
</script>

<style lang="less" scoped>
</style>
