# RPC框架iris

iris是服务治理平台提供的RPC框架，兼容多种序列化协议：JSON /hessian/protobuf等，能够最大限度的适应应用的数据传输需求。基于长连接复用的网络传输层，能够高效的进行网络数据传输。  

iris提供基于注解方式直接发布POJO接口RPC功能，让应用能够最小侵入性和便捷的对外发布RPC接口。RPC接口支持方法粒度的访问权限控制，通过私有加授权的方式，可以设置RPC调用白名单，保障接口的安全性。
![](weifuwujiagou-3.png)
![](weifuwujiagou-4.png)
**接口授权图**