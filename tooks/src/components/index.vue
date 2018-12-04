<template>
  <div class="page-container">
    <el-row>
      <el-col :span="24"><div class="grid-content bg-purple-dark"></div></el-col>
    </el-row>
    <!-- 基本概况 -->
    学生姓名：
    年级：
    学期：
    学科：
    考试时间：
    考试性质：
    老师姓名：

    <!-- 考试情况 -->
    本次考试满分：
    该同学得分：
    班级最高分：
    班级平均分：
    班级排名：
    最高分分差：
    平均分差：

    <!-- 知识体系分析 -->
    1.考察范围：

    2.试卷难度：

    3.知识图谱：


    <!-- 失分情况柱状图 -->





  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<style lang="stylus" scoped>

</style>
