# shark-rpc

## shark-rpc是什么?
一款rpc框架，支持灵活配置

## shark-rpc有哪些功能？

* 基于JDK动态代理、与spring框架集成
* 支持自定义SPI机制
* 支持多种序列化方式：hession、kyro……,通过spi机制实现灵活配置
* 支持压缩解压缩
* 支持多种负载均衡策略(随机、加权随机、轮询、加权轮询、平滑加权轮询、一致性哈希)等
* 提供类dubbo容错机制：failover ，failsafe，failfase ，failback等
* 使用netty作为网络传输层，高效处理传输过程中拆包粘包问题
* 使用zookeeper作为注册中心，提供服务的自动注册发现机制
* 使用本地缓存，提供容错机制
* 使用线程池、CompletableFuture提高性能
* ……

## 有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件: yanyapan@qq.com
* 微信: 18816782469
* 博客: [闫亚攀](https://www.cnblogs.com/yanyapan/)

## 捐助开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一下。


## 关于作者

```javascript
var console = {
  name  : "闫亚攀"
}
```
