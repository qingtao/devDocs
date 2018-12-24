# 浏览器跨域预检请求OPTIONS

### 1. Golang处理跨域你响应时增加："Access-Control-Allow-Origin"
### 2. 如果浏览器触发复杂请求,见[HTTP_CORS](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Access_control_CORS)

> 服务端需要响应：OPTIONS方法：

> 并增加响应头：

> "Access-Control-Allow-Headers", "Content-Type, Authorization, Origin"
"Access-Control-Allow-Origin", "*"(示例)
