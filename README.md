# 仿落网
模板引擎+用不同的方法发送ajax请求
## 应用到的知识
- 模板引擎
- 封装函数
- 异步请求
- jQuery中方法ajax的用法
- PHP中读取文件的方法 
### mater
master中的01.index_原生ajax.html中主要运用的是ajax五步曲：
1. 创建异步对象
2. 设置请求的URL等参数
3. 发送请求
4. 注册事件
5. 在注册事件中获取返回内容并修改页面
### develop
develop分支中的02.index_封装ajax.html是将ajax五步曲封装成一个函数，再用script标签引入ajax_tool.js
### feature
feature分支中的03.index_jq是直接引入jquery框架，再发送get请求
