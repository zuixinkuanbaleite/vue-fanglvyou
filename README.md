## 项目涉及到技术栈：
- vue：Vue、Vue-router、Vuex、Vue-cli 
- 插件：vue-awesome-swiper、better-scroll Axios 
- CSS的预处理框架 stylus 
- api 后台数据接口 
## 主要特点 
- 组件化自适应布局 
- 代码，简洁，易维护 
- 兼容大部分浏览器 
- 性能优化 




# 项目准备
- 导入了reset.css，初始化了项目的一些基本样式。
- 因为是移动app，所以需要在index.html里面需要对meta标签进行修改

intial-scale:页面首次被显示是可视区域的缩放级别，取值1.0则页面按实际尺寸显示，无任何缩放 maximum-scale=1.0, minimum-scale=1.0;可视区域的缩放级别， maximum-scale用户可将页面放大的程序，1.0将禁止用户放大到实际尺寸之上。 user-scalable:是否可对页面进行缩放，no 禁止缩放
## 项目结构部分 
### Header部分 
- 引入 Iconfont 
- 首页轮播 
- 图标区域轮播 
- 使用axios获取接口数据 
- 组件间数据传递 
### 城市选择页面开发 
- Better-scroll的使用和字母表布局 
- eventbus 传值 
- 列表性能优化 
- 搜索逻辑实现 
- Vuex实现数据共享 
- LocalStorage实现页面数据持久存储 
- 使用keep-alive优化路由页面性能 
## 详情页面开发 
- 动态路由配置及banner布局 
- 公用画廊组件拆分 
- 渐隐渐显的header效果实现 
- 递归组件实现详情列表 
- 画廊动画效果封装 

- 样式穿透：突破scope的限制,由于scope的限制，所以定义不起作用，使用/deep/标签可以突破scope的限制。

.wrapper /deep/ .swiper-pagination-bullet-active{
    background: #fff;
}


[项目源码](https://github.com/zuixinkuanbaleite/vue-fanglvyou)
