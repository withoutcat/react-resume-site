<img src="https://github.com/withoutcat/img/blob/main/70x100%E9%95%BF%E6%96%B9%E5%BD%A2%E6%AF%94%E4%BE%8B.jpg?raw=true" style="position:absolute;width:90px;top: 40px;right: 50px;">

# 孙子文 - 后端工程师 - Java

::: left

icon:info 男/1988.07
icon:phone icon:weixin 15524676650
icon:email sunziwens@gmail.com

[icon:github https://github.com/withoutcat](https://github.com/withoutcat)

:::

::: right

:::

## 技能
**Java**
- 掌握多线程与高并发，JUC工具包
- 熟悉JVM(HotSpot)中Synchronized底层原理
- 熟悉基于GoF的23种设计模式
- 常用算法及数据结构
  

**数据库**
- 熟练使用MySQL，且有编写复杂SQL的能力
- 精通Redis及其各项配置
  

**系统/环境**
- 熟练使用Linux(Ubuntu,CentOS)操作指令及其内核epoll原理
  

**框架**
- 掌握Spring Boot、MyBatis、Struts2等主流开发框架
  

**前端**
- ES5/6基础知识及API、Vue.js、JQuery.js
- 有维护Vue-cli和Typescript项目的经验
  

**微服务**
- 熟悉基于AWS平台、Typescript微服务项目的开发
  

**工具**
- Git、SVN、Mave、Markdown
- Intellij IDEA、VSCode、Eclipse

## 个人优势
**懂得自我投资**：每年花在知识付费平均5000元以上
**持续进步**： 会在工作之余坚持学习，每周保证3-10个小时的学习
**语言**：英语可读写可日常对话，因为韩国留学5年韩语比较好

## 教育经历
:::left
**韩国东国大学 - 食品产业管理**
[查看毕业证](https://s6.jpg.cm/2022/01/16/LFtgaX.jpg)
[查看学历认证](https://s6.jpg.cm/2022/01/16/LFt0dD.jpg)


:::
:::right
**2010.09 - 2015.07**
:::




## 工作经历


:::left
**东软集团股份有限公司  - 高级软件开发工程师**
:::
:::right
**2021.9 - Now**
:::

- 经过小半个月的代码熟悉，进入了开发组参与了项目开发
- 多个项目开发包括在AWS上开发微服务项目
- 参与了东软的一些Geek竞赛，曾获得了价值高达100元的好利来蛋糕卡


:::left
**大连众晖科技发展有限公司  - 软件开发工程师**
:::
:::right
**2020.07 - 2021.08**
:::

- 参与多个线上项目的维护工作
- 能力提高进入了开发小组，参与了几个项目的开发
- 承担了一些对新同事的和迎接实习生的带领工作
- 多方接口对接工作


:::left
**大连海控科技有限公司  - Java开发实习工程师**
:::
:::right
**2019.11 - 2020.06**
:::

- 在大连海蓝达学习Java开发，并以优异的成绩被推荐到海控科技实习
- 修改以往项目bug以及维护若干项目
- 项目的CI/CD


:::left
**大连龙慧商贸有限公司  - 采购专员**
:::
:::right
**2015.10 - 2019.10**
:::

- 毕业之后选择了跟自己专业对口的一份工作，对韩进口贸易。工作了4年多的时间。







## 项目
### DWCL
`AWS` `Express` `Node.js` `Typescript` 

- **项目描述**：
	对日项目，是一家日本企业使用的多人在线协同编辑文档的云盘，文档数据通过websocket实时同步所有终端
- **工作内容**：
  - 完成每期的“票”，一般是一些小功能开发和BUG修复
  - 在东软接触了很优秀的多人协同开发流程以及代码管理，工作中代码风格严格按照Google Style Guides
  - 参与补全大量的单元测试代码
  - 对接DocuSign的登录接口
  - 因此项目是完全基于AWS开发，所以学习了很多关于AWS的使用以及CI/CD




### M3德国马牌下单系统
`Struts2` `MySQL` `FreeMarkder` `Vue.js` `Nginx` `JQuery`

- **项目描述**：
	该项目是上海一家礼品定制公司专门针对德国马牌客户制作的下单系统
- **工作内容**：
  - 因该项目是base另一个项目代码，所以修改了很多奇奇怪怪的BUG
  - 通过使用ReentrantLock实现公平锁解决了多年一直存在的诡异数据异常的问题
  - 写定时任务大半夜自动比对库存，然后给开发者发邮件
  - 修改优化Mybatis XML中的长达7600多行的屎山SQL语句
  - 多处日志埋点用于检测数据
  - 多次设计数据库新表用于满足客户提出的聪明绝顶的业务变更
  - 对接快递100
  - 对接第三方系统的代理下单业务

### access订单管理系统
`Springboot` `MySQL` `Vue.js` `Nginx` `JQuery`

- **项目描述**：
	该项目是上海一家礼品定制公司的内部管理系统，主要托管该公司的订单和各种开票业务
- **工作内容**：
  - 因该项目开发周期短，前端页面使用Vue.js + JQuery.js混合使用，修改了很多因此产生的小BUG
  - 通过重写一些页面的js，合理利用async await规避了一些代码绕圈圈的运行
  - 持续开发客户提出的功能和各种奇怪的按钮
  - 补全了后台的信息校验防止了一些懂编程的客户在前段发一些攻击性的请求
  - 采用Nginx做反向代理