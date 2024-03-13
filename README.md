# 求职意向
  Java 开发工程师
# 工作经历
- **塔塔信息技术股份有限公司**
  - 岗位：Java 开发工程师 
  - 年限：2021.12 - 至今
- **艾利安人才服务公司**
  - 岗位：Java 开发工程师
  - 年限：2020.08 - 2021.11

# 教育经历
- **长江大学**
  - 计算机科学与技术  2019.07  学士毕业
# 技术栈
- **语言**：熟练使用Java / Vue.js，了解 C、Python、JavaScript、Shell、SwiftUI 语言。
- **框架**：熟练使用 Spring Boot 后端开发框架，熟练使用 uniapp 前端开发框架。熟练使用 Maven、Gradle 项目构建工具。熟悉 Spring Cloud 、Spring Cloud Alibaba 微服务框架。熟悉其常用组件，如 Nacos、Ribbon、Hystrix、OpenFeign 等。熟悉 SpringFramework。
- **测试**：熟练使用 JUnit、TestNG、Mockito测试框架，熟悉 Selenium 自动化测试框架。 
- **数据库**：熟练使用MySQL、Oracle关系型数据库，Mybatis、Mybatis Plus 等ORM框架。
- **容器化**：熟悉 Docker 容器引擎，了解 Kubernetes (K8s) 容器化管理工具。
- **敏捷开发**：熟练使用 Git / SVN + SonarQube + Jenkins 持续集成自动化部署工具。掌握 CI & CD 理念，熟悉 Scrum 敏捷项目管理模式。
- **其它**：熟悉 Redis、MQ 等中间件。熟悉常用设计模式，如领域驱动设计 (DDD) 等。

# 工作经历
## 塔塔信息技术股份有限公司					                 2021.12 - 至今

- **项目描述**：Study Payment Accelerator。基于开源的 RouYi-Vue 前后端分离后台管理系统，集成流程引擎 Flowable。具有受试信息录入、多种类流程发起、金额计算、审批、邮件通知等功能。
  - 负责 Master Data 信息录入及展示功能开发，使用 POI 工具类解析用户上传的受试项目表格，在后端进行格式及数据完整性校验，最终将处理后的数据存储数据库，文件存入服务器端MinIO文件存储系统。
  - 使用 JavaScript  Lodash 工具库对用户此次上传的数据与数据库里的数据进行逐项对比，结合 ElementUI Table 组件提供的 row-class-name 方法将差异项高亮并以列表文字形式展示。
  - 结合 Floawble 开发审批发起功能，根据不同的金额类别收集具体的金额的信息，在后端进行金额计算后，统一发送给 Flowable 引擎开启流程。
  - 负责开发邮件发送功能，通过监听 Floawble 中节点状态的变化，根据审批类型的不同生成不同的邮件内容。计算在同一个 StudyID、SiteID、合同生效日期下历次审批的总金额与金额上限的百分比，做金额上限的提示。
    
    **关键点：** 全栈开发、Flowable 流程引擎、关系型数据库、模块化设计、报表制作

-  **项目描述：** Customer 360。该应用由跨平台应用框架 Uniapp  （基于Vue 3）开发，具有消息推送、FaceID、地图、多部门权限管理，可视化图表等功能。

    - 负责 Customer Profile 页面开发，使用递归渲染层级组件，展示当前客户所处的 Hierarchy 层级及整体的树形结构。使用 Vue 的组合选项 provide / inject 代替 props, this.$emit() 来解决深层嵌套组件无法与根组件传值和通讯的问题。
    - 基于 web-view 方式集成赛默飞 CyberArk SSO, 编写登录逻辑，编写登录成功之后的接口预处理逻辑，比如获取用户信息，获取当前设备地理位置信息，获取用户所在的 Group 及 Division 信息等。
    - 借助uniapp 全局变量机制glabalData实现权限功能的开发。编写 Setting 的权限及单个页面的 filter 功能代码。

    **关键点**：移动端开发、IOS 开发、Vue.js、TestFlight、Uniapp、团队合作

## 艾利安人才服务公司						2020.08 - 2021.11

- 基于RestAssured 接口自动化框架二次开发 BEAuto 自动化测试平台，技术架构为 Spring Boot  + Redis + ElementUI + jsPlumb + Selenium+ JDK 1.8。使用多线程 + 定时任务执行测试用例。
- Web UI 模块 引入了图形化流程设计 jsPlumb，通过与 Selenium 的结合，使用户可以在浏览器上通过图形化的方式进行 Web UI 的测试脚本编写。
- 重构原有的前端项目代码结构，将js 实现代码与 Vue组件代码分离，采用组件引用方式组合代码，抽出公共组件与公共方法。
- 负责开发用户登录模块，使用了Spring Boot  的 AOP 特性来完成对用户登录信息的获取与存储，以及全局异常的管理，来配合后续测试执行计划的创建与执行。 
- 负责集成了 SpringScurity，使用 WebSecurityConfig 配置常用拦截地址，进一步提升项目的安全性。
- 负责集成了 Redis, Jekenis, SonarQube 等中间件，负责它们的配置维护与更新。

    **关键点：** 全栈开发、自动化测试、Selenium、组内成员代码审核、Jira 集成、从 0 到 1

# 获奖经历
- 剑桥商务英语 B1 
- 国家励志奖学金
- 挑战杯创新创业大赛湖北省二等奖
- 全国大学生数学建模竞赛湖北省一等奖

# 简历 PDF 预览
<img width="910" alt="image" src="https://github.com/wangshicheng1995/cv/assets/63381207/a322504b-c4d9-4c26-ba80-66f8830c4cec">
<img width="873" alt="image" src="https://github.com/wangshicheng1995/cv/assets/63381207/d3b82603-b194-422d-a2d6-9625a9ee53d1">






