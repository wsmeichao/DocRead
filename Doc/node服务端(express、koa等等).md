# Nodejs服务端知识梳理

核心原理：使用node的http(https/http2).creatServer,对某一端口进行监听，当客户端连接时，在creatServer的回调函数中进行相应,然后对request、response进行一系列的处理，

> 本文是基于express4、koa2来阐述的 

express原理介绍：

koa原理介绍：

相同点、差异点、优缺点：


# 核心函数：http.creatServer的戒心，表层到底层这样，具体调用的是底层的TCP链接


