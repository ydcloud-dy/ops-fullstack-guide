# 🚀 运维与后端全栈学习笔记

![GitHub Repo stars](https://img.shields.io/github/stars/yourname/yourrepo?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourname/yourrepo?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/yourname/yourrepo)
![Issues](https://img.shields.io/github/issues/yourname/yourrepo)
![License](https://img.shields.io/github/license/yourname/yourrepo)

---

## 📖 简介
本仓库是一个 **面向运维工程师、后端开发、DevOps 从业者** 的学习笔记与实践指南，涵盖从 **Linux 基础** 到 **云原生架构**、从 **数据库** 到 **CI/CD 自动化** 的完整知识体系。  

目标是：
- 梳理日常工作中运维与开发的核心技术栈  
- 记录学习笔记 & 实践案例  
- 分享生产环境常见问题及解决方案  

---

## 📚 目录导航

- [☸️ 容器与编排](#️-容器与编排)
- [📊 监控与链路追踪](#-监控与链路追踪)
- [📝 日志采集与集中管理](#-日志采集与集中管理)
- [🐹 后端开发与脚本](#-后端开发与脚本)
- [🐧 操作系统与基础设施](#-操作系统与基础设施)
- [💾 数据存储](#-数据存储)
- [📡 消息队列](#-消息队列)
- [🗃 大数据](#-大数据)
- [🔄 持续集成与持续交付-CICD](#-持续集成与持续交付-cicd)
- [🎯 适合人群](#-适合人群)
- [🛠 技术栈一览](#-技术栈一览)
- [📌 使用说明](#-使用说明)
- [📅 更新计划](#-更新计划)

---

## ☸️ 容器与编排
- **Kubernetes**
  - 集群搭建与管理
  - 核心对象：Pod / Service / Deployment / StatefulSet
  - 存储、网络策略与调度优化
  - Helm 与 Operator 实践
- **Ceph 分布式存储**
  - RADOS / RBD / CephFS
  - 集群部署与日常运维
  - 常见问题与数据恢复方案

---

## 📊 监控与链路追踪
- **监控体系**
  - Prometheus 部署与告警
  - VictoriaMetrics 高性能时序存储
  - Grafana 可视化
- **链路追踪**
  - SkyWalking 应用性能监控
  - OpenTelemetry 使用与集成

---

## 📝 日志采集与集中管理
- **日志收集**
  - EFK（Elasticsearch + Fluentd + Kibana）
  - Loki、VictoriaLogs、OpenObserve 替代方案
- **集中分析**
  - 日志归档与查询优化
  - 企业常见最佳实践  

---

## 🐹 后端开发与脚本
- **Golang**
  - 语法基础与标准库
  - 并发编程（goroutine、channel）
  - 常见框架与微服务开发  

---

## 🐧 操作系统与基础设施
- **Linux**
  - 常见命令集合
  - Shell 脚本编写
  - 系统调优与安全加固

---

## 💾 数据存储
- **MySQL**
  - 安装与主从复制
  - 分库分表与高可用架构
  - 性能调优与索引优化
- **Redis**
  - 主从 & 哨兵 & Cluster 集群
  - 缓存穿透、击穿、雪崩解决方案
  - 高可用方案与持久化机制  

---

## 📡 消息队列
- **Kafka**
  - Topic 管理与分区机制
  - 消费者组与偏移量管理
  - 监控与扩展

---

## 🗃 大数据
- **Hadoop 生态**
  - HDFS 基础
  - 数据存储和计算框架概览

---

## 🔄 持续集成与持续交付 (CI/CD)
- Jenkins 流水线
- Tekton 云原生 CI/CD
- ArgoCD GitOps 实践
- Zidlg 部署流程

---

## 🎯 适合人群
- 运维工程师 / DevOps 工程师  
- 后端开发工程师  
- 对云原生 & 自动化感兴趣的学习者  
- 团队内部知识沉淀  

---

## 🛠 技术栈一览
`Kubernetes` · `Ceph` · `Prometheus` · `Grafana` · `SkyWalking`  
`ELK/EFK` · `VictoriaLogs` · `OpenObserve` · `Golang`  
`Linux` · `MySQL` · `Redis` · `Kafka` · `Hadoop`  
`Jenkins` · `Tekton` · `ArgoCD` · `GitOps`  

---

## 📌 使用说明
```bash
# 克隆仓库
git clone https://github.com/yourname/yourrepo.git

# 进入目录
cd yourrepo

# 按需浏览相应模块
