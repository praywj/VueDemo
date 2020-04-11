# VueDemo
基于Vue实现一个todoList应用

主要知识点在于拆分组件、定义组件以及组件间的通信

 vue 组件间通信方式
1) props
2) vue 的自定义事件
3) 消息订阅与发布(如: pubsub 库)   对于祖孙、兄弟组件通信非常简便
4) slot
5) vuex

此处实现了前三种，使用第三种是需要安装`pubsub-js`库
