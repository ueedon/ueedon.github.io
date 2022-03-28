---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

### spring cloud 版本与组件版本

#### spring cloud 官方

|Component|Finchley.SR4|2020.5|2021.0.1|
|----|----|----|----|
|Spring Boot|2.0.x|2.4.x, 2.5.x (Starting with 2020.0.3)|2.6.x|
|Spring Cloud Netflix |2.0.4.RELEASE|3.0.6|3.1.1|
|Spring Cloud Config|2.0.5.RELEASE|3.0.6|3.1.1|
|Spring Cloud Sleuth |2.0.4.RELEASE|3.0.5|3.1.1|
|Spring Cloud Gateway|2.0.4.RELEASE|3.0.5|3.1.1|
|Spring Cloud Commons|2.0.4.RELEASE|3.0.3|3.1.1|
|Spring Cloud Openfeign|2.0.4.RELEASE|3.0.6|3.1.1|
|Spring Cloud Dependencies|Finchley.SR4|2020.5|2021.0.1|
|Spring Cloud Contract |2.0.4.RELEASE|3.0.5|3.1.1|
|Spring Cloud Kubernetes |-|2.0.5|2.1.1|
|Spring Cloud Zookeeper|2.0.2.RELEASE|3.0.5|3.1.1|
|Spring Cloud Circuitbreaker|-|-|2.1.1|
|Spring Cloud Task|2.0.2.RELEASE|2.3.5|2.4.1|
|Spring Cloud Build|2.0.6.RELEASE|2020.0.5|2021.0.1|
|Spring Cloud Cloudfoundry|2.0.2.RELEASE|3.0.3|3.1.0|
|Spring Cloud Cli|2.0.4.RELEASE|3.0.5|3.1.0|
|Spring Cloud Vault|2.0.4.RELEASE|3.0.5|3.1.0|
|Spring Cloud Security|2.0.2.RELEASE|----|----|
|Spring Cloud Consul |2.0.3.RELEASE|----|3.1.0|
|Spring Cloud Function |1.0.2.RELEASE|----|----|
|Spring Cloud Aws |2.0.3.RELEASE|----|----|
|Spring Cloud Release|Finchley.SR4|----|----|
|Spring Cloud Bus |2.0.2.RELEASE|----|3.1.0|
|Spring Cloud Stream|Elmhurst.SR3|----|----|

从2020版本开始 以下spring-cloud-netflix 组件被移除
- spring-cloud-netflix-archaius
- spring-cloud-netflix-concurrency-limits
- spring-cloud-netflix-core
- spring-cloud-netflix-dependencies
- spring-cloud-netflix-hystrix
- spring-cloud-netflix-hystrix-contract
- spring-cloud-netflix-hystrix-dashboard
- spring-cloud-netflix-hystrix-stream
- spring-cloud-netflix-ribbon
- spring-cloud-netflix-sidecar
- spring-cloud-netflix-turbine
- spring-cloud-netflix-turbine-stream
- spring-cloud-netflix-zuul
- spring-cloud-starter-netflix-archaius
- spring-cloud-starter-netflix-hystrix
- spring-cloud-starter-netflix-hystrix-dashboard
- spring-cloud-starter-netflix-ribbon
- spring-cloud-starter-netflix-turbine
- spring-cloud-starter-netflix-turbine-stream
- spring-cloud-starter-netflix-zuul
- Support for ribbon, hystrix and zuul was removed across the release train projects.

参考：
- [spring cloud A-H](https://github.com/spring-projects/spring-cloud/wiki/Spring-Cloud-Finchley-Release-Notes)
- [spring cloud 2020+](https://github.com/spring-cloud/spring-cloud-release/wiki/Spring-Cloud-2020.0-Release-Notes)

spring cloud 版本线与生命周期

| 版本线       | 生命周期      | 兼容 Spring Boot 版本                    |
| --------- | --------- | ------------------------------------ |
| 2022.x    | 未发布       | Spring Boot 3.0                      |
| 2021.x    | 未知        | Spring Boot 2.6.1                    |
| 2020.x    | 未知        | Spring Boot 2.4.x, 2.5.x (2020.0.3+) |
| Hoxton    | 2022/2/28 | Spring Boot 2.2.x, 2.3.x (SR5+)      |
| Greenwich | 已停止维护     | Spring Boot 2.1.x                    |
| Finchley  | 已停止维护     | Spring Boot 2.0.x                    |
| Edgware   | 已停止维护     | Spring Boot 1.5.x                    |
| Dalston   | 已停止维护     | Spring Boot 1.5.x                    |

spring boot 版本线与生命周期

| 版本                                                                                                                                                                                    | 发布时间       | 停止维护时间     | 停止商业支持    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | --------- |
| 2.7.0                                                                                                                                                                                 | 2022/5/19  | 2023/5/18  | 2024/8/22 |
| [2.6.0](https://link.segmentfault.com/?enc=4hevBD5C2H9gYvi7B4VVvA%3D%3D.%2B1j3V8zSzFxQXV4mBF26CIRBnjkh1lw5c1e%2Bj6z0QS%2FSXAZj%2BPC%2BmmAdNkleHmU4FXc0n4iJ%2Bpug05sRuQQ9KA%3D%3D)     | 2021/12/17 | 2022/11/24 | 2024/2/24 |
| [2.5.x](https://link.segmentfault.com/?enc=vZk3mpoWkliZWozLafKIMA%3D%3D.x41xufzhkZHguFE4BetHaBxqDhQPNqivHEFqA1VBEAnCQYY0f2AHAdVE%2FPUnHVB9gJrrrA7xlC227MQnOFg2rA%3D%3D)               | 2021/5/20  | 2022/5/19  | 2023/8/24 |
| [2.4.x](https://link.segmentfault.com/?enc=9wKXfwRyEgUoFFAVd8Fjsg%3D%3D.RuqAplPmqfJEwTuSGbFdak70RjGR57fQMXiaavFXqalimNNXoHGMFzt%2FXFGnCjTLnGdTZ3j2sK0uMChyPtSl4Q%3D%3D)               | 2020/11/12 | 已停止        | 2023/2/23 |
| [2.3.x](https://link.segmentfault.com/?enc=kXirhSt4ItdbTy319lGNyw%3D%3D.5yHuHARrR56ZXoT4YZDdJUyjdHNlLtCp6AH8UJUMqfTTvDi1y36%2F6RfmFaPfYX96RYPEM1ohQ%2BVzROTRCKUhbA%3D%3D)             | 2020/5/15  | 已停止        | 2022/8/20 |
| [2.2.x](https://link.segmentfault.com/?enc=ZGe19vZ0n%2BILkW32oS2Jvg%3D%3D.w0Nqf%2BId91dt8SHhKo7zpcPnzqLt5MRISOUMXhm51DYtrTgdJcoMP8ziJ9OS5CECR6iMWf9%2BDIxygWa5m5bNkA%3D%3D)           | 2019/10/16 | 已停止        | 已停止       |
| [2.1.x](https://link.segmentfault.com/?enc=fiXLTctjPuS92Tm2V960cg%3D%3D.WrEU2WYviBjg%2BGE6cnmA3CfrN1YKLBbB7A9dPEA%2BZsSG5fkhbtUZgOe2CVvSy6ML5F3RTpGOBvzUnm1oZTkS0g%3D%3D)             | 2018/10/10 | 已停止        | 已停止       |
| [2.0.x](https://link.segmentfault.com/?enc=rj5Lnq%2F5BOuMOUqJOItP0w%3D%3D.k%2F4RQlwrk9EmKKfh%2FWWEhsxZWpVVYpYBqC6JJGQYX%2FxnMLpGo7BKZO%2BRsGVgoOG1QHA%2Bri5k6wWA3Wp60gw8ig%3D%3D)     | 2018/3/1   | 已停止        | 已停止       |
| [1.5.x](https://link.segmentfault.com/?enc=7%2Fe7LD%2Foqb%2BI8Kmaw0l08w%3D%3D.ltChJm2%2BY0V2N60fLdE92hdYpZZUC%2FXzgFMk5hWvgAAmpblASAhjS%2BmxFQMvAqP6WN6KXN6JG%2FzwOo9Kh0L%2Ffw%3D%3D) | 2017/1/30  | 已停止        | 已停止       |

#### spring cloud alibaba
组件版本关系

| Spring Cloud Alibaba Version                              | Sentinel Version | Nacos Version | RocketMQ Version | Dubbo Version | Seata Version |
| --------------------------------------------------------- | ---------------- | ------------- | ---------------- | ------------- | ------------- |
| 2021.0.1.0\*                                              | 1.8.3            | 1.4.2         | 4.9.2            | 2.7.15        | 1.4.2         |
| 2.2.7.RELEASE                                             | 1.8.1            | 2.0.3         | 4.6.1            | 2.7.13        | 1.3.0         |
| 2.2.6.RELEASE                                             | 1.8.1            | 1.4.2         | 4.4.0            | 2.7.8         | 1.3.0         |
| 2021.1 or 2.2.5.RELEASE or 2.1.4.RELEASE or 2.0.4.RELEASE | 1.8.0            | 1.4.1         | 4.4.0            | 2.7.8         | 1.3.0         |
| 2.2.3.RELEASE or 2.1.3.RELEASE or 2.0.3.RELEASE           | 1.8.0            | 1.3.3         | 4.4.0            | 2.7.8         | 1.3.0         |
| 2.2.1.RELEASE or 2.1.2.RELEASE or 2.0.2.RELEASE           | 1.7.1            | 1.2.1         | 4.4.0            | 2.7.6         | 1.2.0         |
| 2.2.0.RELEASE                                             | 1.7.1            | 1.1.4         | 4.4.0            | 2.7.4.1       | 1.0.0         |
| 2.1.1.RELEASE or 2.0.1.RELEASE or 1.5.1.RELEASE           | 1.7.0            | 1.1.4         | 4.4.0            | 2.7.3         | 0.9.0         |
| 2.1.0.RELEASE or 2.0.0.RELEASE or 1.5.0.RELEASE           | 1.6.3            | 1.1.1         | 4.4.0            | 2.7.3         | 0.7.1         |

毕业版本依赖关系(推荐使用)
下表为按时间顺序发布的 Spring Cloud Alibaba 以及对应的适配 Spring Cloud 和 Spring Boot 版本关系（由于 Spring Cloud 版本命名有调整，所以对应的 Spring Cloud Alibaba 版本号也做了对应变化）

| Spring Cloud Alibaba Version | Spring Cloud Version        | Spring Boot Version |
| ---------------------------- | --------------------------- | ------------------- |
| 2021.0.1.0                   | Spring Cloud 2021.0.1       | 2.6.3               |
| 2.2.7.RELEASE                | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2021.1                       | Spring Cloud 2020.0.1       | 2.4.2               |
| 2.2.6.RELEASE                | Spring Cloud Hoxton.SR9     | 2.3.2.RELEASE       |
| 2.1.4.RELEASE                | Spring Cloud Greenwich.SR6  | 2.1.13.RELEASE      |
| 2.2.1.RELEASE                | Spring Cloud Hoxton.SR3     | 2.2.5.RELEASE       |
| 2.2.0.RELEASE                | Spring Cloud Hoxton.RELEASE | 2.2.X.RELEASE       |
| 2.1.2.RELEASE                | Spring Cloud Greenwich      | 2.1.X.RELEASE       |
| 2.0.4.RELEASE(停止维护，建议升级)     | Spring Cloud Finchley       | 2.0.X.RELEASE       |
| 1.5.1.RELEASE(停止维护，建议升级)     | Spring Cloud Edgware        | 1.5.X.RELEASE       |
