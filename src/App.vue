<template>
  <div>
    <button
      @mousedown="handleMouseDown"
      @mouseup="handleMouseUp"
      @click="handleClick"
    >
      点击我
    </button>
  </div>
</template>

<script>
export default {
  methods: {
    handleMouseDown() {
      console.log('鼠标按下，执行事件1');
      // 在这里执行事件1的操作
    },
    handleMouseUp() {
      console.log('鼠标松开，执行事件2');
      // 在这里执行事件2的操作
    },
    handleClick() {
      console.log('按钮被点击');
      // 如果您需要处理点击事件，也可以在这里执行相应的操作
    },
  },
};
</script>
