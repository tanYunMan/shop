<template>
  <div id="app">
    <!-- <keep-alive> -->
    <router-view />
    <!-- </keep-alive> -->
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>
<style lang="scss">
body .el-table th.gutter {
  display: table-cell !important;
}
</style>
<style>
.faka-table-header th {
  /* background: #dbdbdb !important; */
  color: #515151;;
}

/* 设置输入框提示文字颜色 */
::-webkit-input-placeholder { /* WebKit browsers */
  color: gray !important;
}

::-moz-placeholder { /* Mozilla Firefox 19+ */
  color: gray !important;
}

:-ms-input-placeholder { /* Internet Explorer 10+ */
  color: gray !important;
}
.search-container .el-form {
  padding: 0;
}

.el-dialog__header {
    padding: 10px 20px !important;
}

.el-dialog__headerbtn {
    top: 15px !important;
}
.el-input__inner{
  padding: 2px;
  font-size: 13px;
}

.dir_project_box .el-checkbox__label {
  flex: 1;
  overflow: hidden;
  white-space: normal;
}
</style>
