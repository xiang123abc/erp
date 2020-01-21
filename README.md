# myerp

### 介绍
ERP进销存管理系统

### 软件架构
* 核心框架：SpringBoot 2.0.0
* 持久层框架：Mybatis 1.3.2
* 日志管理：Log4j 2.10.0
* JS框架：Jquery 1.8.0
* UI框架: EasyUI 1.3.5
* 模板框架: AdminLTE 2.4.0
* 项目管理框架: Maven 3.2.3

### 开发环境
建议开发者使用以下环境，可以避免版本带来的问题
* IDE: IntelliJ IDEA 2017+
* DB: Mysql5.7.4
* JDK: JDK1.8
* Maven: Maven3.2.3+

### 运行环境
* 数据库服务器：Mysql5.7.4
* JAVA平台: JRE1.8
* 操作系统：Windows、Linux等

### 安装教程
1.下载项目，将源码以Maven的方式导入Eclipse或IDEA中，并关联好JDK。  
项目结构：  
![项目源码结构](https://images.gitee.com/uploads/images/2019/1206/102251_e6a0b87d_5340558.png "屏幕截图.png")  

2.将数据库文件jsh_erp.sql导入MySQL中  
可以提前先在MySQL中创建一个名为jsh_erp的数据库，然后再导入。  

3.打开项目源目录resources中的配置文件application.properties，修改数据库连接、账号、密码。  

4.运行com.jsh.erp包中的ErpApplication类，启动项目。（使用SpringBoot的启动方式）  

5.浏览器地址访问登录页面http://localhost:8080/login.html，  
默认管理员账号：admin，管理员账号一些特殊模块不具有修改权限，建议使用普通账号：jsh，密码都为123456

### 项目截图

![登录页面](https://images.gitee.com/uploads/images/2019/1206/102155_e66fd260_5340558.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/113941_da66ab56_5340558.png "2019-12-05_082557.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/113951_03ad5d86_5340558.png "2019-12-05_082637.png")

![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/114001_c22126ca_5340558.png "2019-12-05_082656.png")
![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/114035_ef42b3e0_5340558.png "2019-12-05_082802.png")
![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/114047_e2f223f4_5340558.png "2019-12-05_083024.png")
![输入图片说明](https://images.gitee.com/uploads/images/2019/1206/114056_fb9ff14c_5340558.png "2019-12-06_085911.png")