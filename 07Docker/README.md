# Docker

## Chapter 1: The Path to Containerized Application 

### 01_introduction

- microservice
- container
- service governance
- immutable platform
- declarative API
- devops

### 02_challenges in deployment

- The deployment process of the application
  - For example, a Java web application deplyed to Tomcat using a WAR file.
- Application scaling(up and down)
- Problems in deploying the application across different environments

### 03_evolution of computing resources
### 04_evolution of computing resources_virtual machine
### 05_evolution of computing resources_container
### 06_What is container
### 07_What problem does container resolve
### 08_History of container

## Chapter 2: Core Linux kernel technologies underpin containerization

### 09 Introduction of container
### 10 Container Technology: From chroot to Kubernetes

- chroot
- FreeBSD Jails
- Linux VServer
- Solaris
- OpenVZ

### 11 NameSpace
### 12 The classification of NameSpace of Linux
### * 13 Use Cases of Network Namespaces in Linux 
### 14 CGroups
### 15 Four Key Functions of Groups
### * 16 Use Case of CGroups
chapter 3: 章节3:Docker生态架构及部署 (3节)
课时17


01_容器管理工具_Docker生态架构及部署_生态架构介绍

15分16秒

课时18


02_管理管理工具_Docker生态架构及部署_Docker安装_YUM安装方式

15分51秒

课时19


03_管理管理工具_Docker生态架构及部署_Docker安装_二进制安装方式

10分29秒

章节4:使用容器运行Nginx及docker命令介绍 (11节)
课时20


在容器中运行nginx

12分58秒

课时21


获取Docker命令帮助方法

4分38秒

课时22


docker run命令

8分43秒

课时23


docker ps命令

1分50秒

课时24


docker inspect命令

3分19秒

课时25


docker exec命令

2分26秒

课时26


docker attach命令

3分26秒

课时27


docker stop命令

2分2秒

课时28


docker start命令

1分56秒

课时29


docker top命令

4分15秒

课时30


docker rm命令

7分56秒

章节5:容器镜像介绍及应用 (14节)
课时31


docker容器镜像查看

6分27秒

课时32


docker容器镜像搜索

6分6秒

课时33


docker容器镜像下载

4分37秒

课时34


docker容器镜像删除

4分25秒

课时35


docker容器镜像定义

3分58秒

课时36


联合文件系统

3分13秒

课时37


存储驱动方式

7分31秒

课时38


docker容器镜像分层

14分31秒

课时39


docker容器与镜像之间的关系

7分10秒

课时40


docker容器中添加内容后容器与镜像的变化

8分41秒

课时41


docker commit命令

11分45秒

课时42


docker save命令

2分18秒

课时43


docker load命令

2分31秒

课时44


docker export与docker import命令

4分59秒

章节6:Docker容器镜像加速器及容器镜像仓库 (4节)
课时45


容器镜像加速器

9分48秒

课时46


容器镜像仓库 Docker Hub

14分35秒

课时47

容器镜像仓库 Harbor

18分18秒

课时48


容器镜像仓库 Harbor 上传及下载容器镜像

12分22秒

章节7:Docker容器化部署企业级应用集群 (21节)
课时49


必要性及参考资料

5分51秒

课时50


Nginx部署_获取参考资料

4分24秒

课时51


Nginx部署_运行Nginx容器

8分0秒

课时52


Nginx部署_运行Nginx容器_暴露端口

9分12秒

课时53


Nginx部署_运行Nginx容器_修改配置文件

11分6秒

课时54


部署https访问nginx应用

25分16秒

课时55


Tomcat部署_获取参考资料

2分59秒

课时56


Tomcat部署_运行Tomcat容器

15分11秒

课时57


MySQL部署_获取参考资料

3分27秒

课时58


MySQL部署_单节点MySQL部署

9分19秒

课时59


MySQL主从复制部署_Master节点部署及配置

6分50秒

课时60


MySQL主从复制部署_Slave节点部署及配置

5分42秒

课时61


MySQL主从复制部署_主从复制配置及验证

11分32秒

课时62


Oracle部署

9分28秒

课时63


ElasticSearch及Kibana部署_获取参考资料

4分6秒

课时64


ElasticSearch及Kibana部署_ES部署

6分58秒

课时65


ElasticSearch及Kibana部署_Kibana部署及访问验证

5分48秒

课时66


Redis部署_获取参考资料

2分34秒

课时67


Redis部署_单节点Redis部署

11分26秒

课时68


Redis部署_Redis集群部署

9分0秒

课时69


RabbitMQ部署

6分39秒

章节8:Dockerfile精讲及新型容器镜像构建技术 (14节)
课时70


回顾容器与容器镜像之间的关系

3分9秒

课时71


容器镜像分类

4分8秒

课时72


容器镜像获取方法

2分12秒

课时73


在dockerhub上直接下载

4分23秒

课时74


把操作系统中文件系统打包为镜像

13分54秒

课时75


把正在运行的容器提交为容器镜像

6分37秒

课时76


Dockerfile_介绍

4分42秒

课时77


Dockerfile_指令

16分15秒

课时78


Dockerfile_基本组成

1分52秒

课时79


Dockerfile_生成容器镜像过程

5分8秒

课时80


Dockerfile_生成容器镜像步骤

1分43秒

课时81


Dockerfile_生成Nginx容器镜像

12分20秒

课时82


Dockerfile_生成Tomcat容器镜像

12分2秒

课时83


Dockerfile_生成容器镜像优化的方法

6分59秒

章节9:Docker容器网络与通信原理深度解析 (19节)
课时84


Docker容器默认网络模型

9分8秒

课时85


Docker容器默认网络模型工作原理_容器访问外网

5分32秒

课时86

Docker容器默认网络模型工作原理_外网访问容器

4分2秒

课时87


Docker容器四种网络模型

6分51秒

课时88


网络模型应用案例_查看已有网络模型

6分46秒

课时89


网络模型应用案例_创建bridge类型网络

7分57秒

课时90


网络模型应用案例_应用host类型网络

6分53秒

课时91


网络模型应用案例_应用null类型网络

1分55秒

课时92


网络模型应用案例_应用联盟式类型网络

6分39秒

课时93


跨Docker Host容器间通信_必要性

4分20秒

课时94


跨Docker Host容器间通信_实现方案

3分9秒

课时95


跨Docker Host容器间通信_overlay network介绍

2分38秒

课时96


跨Docker Host容器间通信_Flannel介绍及其工作原理

8分31秒

课时97


跨Docker Host容器间通信_ETCD数据库介绍

2分8秒

课时98


跨Docker Host容器间通信_主机准备

5分1秒

课时99


跨Docker Host容器间通信_etcd部署

12分53秒

课时100


跨Docker Host容器间通信_flannel部署

13分4秒

课时101


跨Docker Host容器间通信_Docker网络配置

5分2秒

课时102


跨Docker Host容器间通信_验证跨Docker Host容器间通信

3分56秒

章节10:Docker容器数据持久化存储机制 (5节)
课时103


容器数据持久化存储必要性

3分0秒

课时104


容器数据持久化存储方式

3分20秒

课时105


容器数据持久化存储方式演示_docker run命令

12分21秒

课时106


容器数据持久化存储方式演示_volumes

6分41秒

课时107


容器数据持久化存储方式演示_bind mounts

4分28秒

章节11:Docker容器服务编排利器 Docker Compose应用实战 (5节)
课时108


使用docker-compose必要性及定义

7分46秒

课时109


使用docker-compose应用参考资料

2分35秒

课时110


docker-compose中概念及实践步骤

3分38秒

课时111


docker-compose安装

3分47秒

课时112


docker-compose应用案例

15分48秒

章节12:Docker主机集群化方案 Docker Swarm (27节)
课时113


Docker Swarm_介绍

5分0秒

课时114


Docker Swarm_概念与架构

8分30秒

课时115


Docker Swarm_集群部署_容器镜像仓库准备及集群主机准备

8分15秒

课时116


Docker Swarm_集群部署_docker安装

5分18秒

课时117


Docker Swarm_集群部署_集群初始化_命令帮助

3分33秒

课时118


Docker Swarm_集群部署_集群初始化_在管理节点完成集群初始化

4分49秒

课时119


Docker Swarm_集群部署_集群初始化_添加工作节点至集群

3分10秒

课时120


Docker Swarm_集群部署_集群初始化_添加管理节点至集群

3分33秒

课时121


Docker Swarm_集群部署_集群初始化_模拟管理节点出现故障

4分28秒

课时122


Docker Swarm_集群应用_服务发布前镜像准备

12分28秒

课时123


Docker Swarm_集群应用_发布服务

11分56秒

课时124


Docker Swarm_集群应用_服务扩缩容

6分57秒

课时125


Docker Swarm_集群应用_服务负载均衡验证

5分54秒

课时126


Docker Swarm_集群应用_服务删除

2分12秒

课时127


Docker Swarm_集群应用_服务版本更新及版本回退

6分26秒

课时128


Docker Swarm_集群应用_服务版本滚动间隔更新

9分38秒

课时129


Docker Swarm_集群应用_副本控制器

4分11秒

课时130


Docker Swarm_集群应用_在指定网络中发布服务

6分35秒

课时131


Docker Swarm_集群应用_服务网络模式

9分6秒

课时132


Docker Swarm_集群应用_服务数据持久化存储

18分40秒

课时133


Docker Swarm_集群应用_服务互联与服务发现

15分16秒

课时134


Docker Swarm_docker stack_介绍

3分40秒

课时135


Docker Swarm_docker stack_与docker compose区别

3分7秒

课时136


Docker Swarm_docker stack_常用命令

1分57秒

课时137


Docker Swarm_docker stack_部署wordpress应用案例

11分39秒

课时138


部署nginx及Docker主机web管理工具应用案例

9分34秒

课时139


docker stack_部署haproxy代理nginx应用案例

12分40秒

章节13:基于Docker容器DevOps应用方案 企业业务代码发布系统 (20节)
课时140


课程介绍及企业业务代码发布方式介绍

4分32秒

课时141


企业业务代码发布逻辑图

4分36秒

课时142


企业业务代码发布工具

5分12秒

课时143


企业业务代码发布流程图

4分17秒

课时144


企业业务代码发布系统环境部署_主机规划

4分39秒

课时145


企业业务代码发布系统环境部署_主机准备

7分22秒

课时146


企业业务代码发布系统环境部署_主机工具安装_dev主机

2分15秒

课时147


企业业务代码发布系统环境部署_主机工具安装_gitlab-server主机

7分51秒

课时148


企业业务代码发布系统环境部署_主机工具安装_jenkins-server主机

17分46秒

课时149


企业业务代码发布系统环境部署_主机工具安装_harbor-server主机

7分40秒

课时150


企业业务代码发布系统环境部署_主机工具安装_web-server主机

2分9秒

课时151


企业业务代码发布系统环境部署_主机工具集成配置

13分32秒

课时152


企业业务代码发布系统环境部署_jenkins插件安装

4分10秒

课时153


企业业务代码发布系统环境部署_jenkins全局工具配置

3分4秒

课时154


企业业务代码发布系统环境部署_jenkins系统配置

3分23秒

课时155


企业业务代码项目发布_数据库管理系统及数据库准备

5分7秒

课时156


企业业务代码项目发布_项目代码获取

2分37秒

课时157


企业业务代码项目发布_推送代码至gitlab仓库

5分17秒

课时158


企业业务代码项目发布_构建容器基础镜像_tomcat

7分25秒

课时159


企业业务代码项目发布_项目构建及发布

16分49秒

章节14:借助Deepseek利用自然语言管理Docker容器 (5节)
课时160


课程内容介绍

更新时间：2025-04-15

5分20秒

课时161


环境说明

更新时间：2025-04-15

2分58秒

课时162


环境准备

更新时间：2025-04-15

13分10秒

课时163


项目构建前准备

更新时间：2025-04-15

23分3秒

课时164


项目构建运行及可用性验证

更新时间：2025-04-15

12分30秒