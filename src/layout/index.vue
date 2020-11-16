<template>
 <div class="layout">
    <el-container>
        <el-header height="80px">Header</el-header>
        <el-container>
          <el-aside width="300px">Aside</el-aside>
          <el-main>Main</el-main>
        </el-container>
    </el-container>
 </div>
</template>
<script>
 export default {
   components: {

   },
   data () {
     return {

     }
   },
   created () {
   },
   mounted () {
   },
   methods: { 

   },
 }
</script>

<style lang='scss'>
  .layout{
      .el-header, .el-footer {
        background-color: #B3C0D1;
        color: #333;
        text-align: center;
        line-height: 80px;
      }
      .el-aside {
        background-color: #D3DCE6;
        color: #333;
        text-align: center;
        // line-height: 200px;
        height: 678px;
        width: 600px;
      }
      
      .el-main {
        background-color: #E9EEF3;
        color: #333;
        text-align: center;
        line-height: 160px;
        min-height: 678px;
      }
      
      body > .el-container {
        margin-bottom: 40px;
      }
      
      .el-container:nth-child(5) .el-aside,
      .el-container:nth-child(6) .el-aside {
        line-height: 260px;
      }
      
      .el-container:nth-child(7) .el-aside {
        line-height: 320px;
      }
  }
</style>
