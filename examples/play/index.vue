<template>
  <el-select v-model="value" placeholder="请选择">
    <el-option v-for="item in options" :key="item.value" :label="item.label" :value="item.value">
    </el-option>
  </el-select>
</template>

<script>
export default {
  data() {
    return {
      options: [
        {
          value: "1",
          label: "黄金糕"
        },
        {
          value: "2",
          label: "双皮奶"
        },
        {
          value: "3",
          label: "蚵仔煎"
        },
        {
          value: "4",
          label: "龙须面"
        },
        {
          value: "5",
          label: "北京烤鸭"
        },
        {
          value: "6",
          label: "炸酱面"
        },
        {
          value: "7",
          label: "烤肉"
        },
        {
          value: "8",
          label: "螺蛳粉"
        },
        {
          value: "9",
          label: "拉面"
        }
      ],
      value: ""
    };
  }
};
</script>