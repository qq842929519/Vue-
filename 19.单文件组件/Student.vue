<template>
    <!-- 组件的结构 -->
    <div class="demo">
     <h2>学生名称：{{name}}</h2>
     <h2>学生年龄：{{age}}</h2>
   </div>
    
</template>

<script>
    //组件交互相关的代码（数据、方法等等）
    export default{
            name:'Student',
            data(){
                return{
                    name:'南邮通达',
                    age:'江苏扬州',
                }  
            },
    }
</script>
<style>
    /* 组件的样式 */
    .demo{
        background-color: orange;
    }
</style>
