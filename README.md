# api
the api document of the project 

### swagger.yaml为本次项目的API文档

### API使用说明[git page地址](https://zhuangwz.github.io/api/)


## 个人总结报告
本次项目我完成的是我们小组的API仓库部分，此部分包含本次项目的API文档设计与GIT PAGE实现。

### API文档设计
    我使用的是老师课上说的YAML语言来设计，使用的工具是SWAGGER Editor。
    YAML相比于JSON，更加灵活，且界面更加直观、通俗易懂。因此用YAML来完成此次API的文档设计更加合适。
    YAML的API内容我按照“星际争战”中的API进行设计的，总共包含了People、StarShips、Planets、Vehicles等六大类。每个类中又同时支持单个ID查询和分页查询，能够按照ID或组号返回相应的内容。
    SWAGGER Editor能够自动识别文档设计中的格式错误，设计过程不易出错。此外，SWAGGER Editor还提供自动生成前端或者后端的测试代码，能够进行前端和后端的分离开发和检验，因此使用SWAGGER Editor工具来完成。
    
### GIT PAGE实现
    Git PAGE使用的则是Hexo工具。Github Pages 支持自动利用Jekyll或Hexo 生成站点，也同样支持纯HTML文档，将你的Jekyll或Hexo站点托管在Github Pages上。而我选择Hexo则是因为Hexo基于Nodejs环境，Nodejs搭建起来较为简单，因此选用Hexo。
    由于此GIT PAGE要实现的是说明文档功能，所以我就把Hexo默认框架中的标题和侧边栏等功能取消掉了，只保留中间的说明文档部分，并且按照YAML中的格式来呈现。
