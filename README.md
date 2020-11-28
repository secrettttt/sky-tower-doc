# SkyTower相关文档汇总

## SkyTower介绍
&#160; &#160; &#160; &#160;AirportTower是机场塔台，或称控制塔，是一种设置于机场中的航空运输管制设施，用来监看以及控制飞机起降的地方。机场塔台里可以监测到当日进出港机组排班情况，延误正点、航班号、计划起飞时间、目的地、机型、停机位、离场信息、应答机号等信息。一般这些信息会在机组起飞或者准备降落时获得。这和我们的网络请求是一样的，当页面向服务端发起请求或者接受响应时，我们如果能够将此次请求相关的参数上报给一个类似“AirportTower”的监控平台，那么我们就可以在这个平台上看到各种各样的监控数据。    
&#160; &#160; &#160; &#160;SkyTower就是借鉴了这个思想，接入SkyTower的前端项目，在项目中部署Emitter，当对应的事件被触发，Emitter就会向SkyTower发射信号。在SkyTower上就能够实时地监测到此次事件。
接入SkyTower，
- 研发能够快速追查线上问题、接收到监控报警，线上bug尽快修复，提升用户体验；
- 产品能够看到用户真实的使用情况数据，更能够站在用户的角度看问题，指导产品的更新迭代；
- 数据分析师能够拿到真实的用户行为数据，做更多有意义的事；
## 相关仓库
- SkyTower监控平台 前端代码仓库： https://github.com/secrettttt/sky-tower-fe
- SkyTower监控平台 服务端代码仓库：https://github.com/secrettttt/sky-tower-server
- SkyTower jssdk工具库代码仓库：https://github.com/secrettttt/sky-tower-jssdk

## 概要设计
https://y5cu4pfrwh.feishu.cn/docs/doccncFMDWZFdOSSf4u5dwnOAnh?from=from_copylink
