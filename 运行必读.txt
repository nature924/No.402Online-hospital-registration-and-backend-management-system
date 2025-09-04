一、项目介绍

基于 Spring Boot 的线上医院挂号与后台管理系统，主要参与角色为：后台管理员、普通用户/会员、专家。主要功能模块和各角色职责如下：

用户 / 会员（前端用户）：
登录/注册/登出/找回密码
浏览专家列表、查看专家详情
发起挂号预约（订单）、查看订单详情、取消预约
论坛发帖/评论、查看专家留言

专家：
专家注册、资料维护、查看个人预约/订单
接收/处理预约（含审核 shenhe）
回应留言、参与论坛互动

后台管理员（管理端）：
用户/会员/专家 管理：分页/列表/详情/新增/修改/删除/批量导入
订单管理：分页/审核/详情/删除
论坛与留言管理：帖子管理、留言管理

二、项目技术
编程语言：Java (后端)、Vue (前端)
项目架构：B/S 架构
后端技术栈（主要）：Spring Boot (父版本 2.2.2.RELEASE)，MyBatis / MyBatis-Plus，自定义 Token 机制（项目依赖包含 Apache Shiro），MySQL（通过 mysql-connector-java），Fastjson，Hutool、，Maven（pom.xml）
前端技术栈（主要）：Vue 2.x、vue-router、Element UI，axios（封装在 src/utils/http.js，自动在请求头加入 Token）

三、运行环境
JDK版本：1.8及以上都可以
操作系统：Windows7/10、MacOS
开发工具：IDEA、Ecplise、MyEclipse都可以
数据库: MySQL5.5/5.7/8.0版本都可以
npm版本：6.14.13及以上都可以
Redis版本：3.2.100及以上都可以


四、数据库配置文件
文件名：application.yml
编码类型：utf8

