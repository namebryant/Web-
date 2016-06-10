#Web后端开发
`开发Web后台需要的基本功以及共通的业务点`

---

##0.基本功

-  HTTP基本概念
-  SQL数据库的基本操作
-  正则表达式
-  Linux/Unix系统的基本操作
-  大型框架选择
    - Python:`Django`
    - Ruby:`Ruby on Rails`
    - PHP: `Laravel`
    - Node.js: `Express/Sails`
    - Java: 'SpringMVC'
    
> 下面是个人总结，有主观因素，内容会一步步添加上去，这个是简单汇总



##1.定义URL路由(`Route`)

-   路由表/路由项
-   路由过滤器



##2.编写/组织请求函数(`Views`)

-   Request Handle函数
-   修改/输出 Response Header/Content
-   实现GET/POST/PUT方法
-   如何获取/修改/存储 cookie/session
-   中间件概念:定义全局拦截函数
-   JSON/XML Parse/文件上传


##3.数据库(`Models`)

-   ORM
-   Sqlite3/MySQL/NoSQL/PostgreSQL/Oracle
-   定义/组织/初始化/修改 数据表 (Django 每个数据模型层的变更都需要makemigrations/migrate)
-   增删改查，直接SQL语句访问
-   ORM中的hasone,manytomany,onetomany关系

##4.模板系统(`Templates`)

-  组织/访问模板文件的目录 /app/templates/...
-  模板语法/继承
-  自定义模板函数
-  include其他模板
-  for/if/else/HTTP操作  

##5.表单(`Form`)

-  表单验证辅助函数
-  安全问题:Auth等

##6.部署/架构(`Deploy`)

-  云服务器
-  域名备案绑定
-  配置开发/生产环境
-  自动化运维
-  如何访问数据库
-  文件架构: 静态文件访问等问题

##7.CMS(`Admin`)

-  Admin 后台管理

##8.其他

-  异常处理,404/403/500/200/201
-  日志系统
-  邮件系统
