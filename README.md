## 欢迎来到phpms框架开发主页

你可在这里查看phpms框架并下载开源源码
### [源码查看](https://github.com/wuxiumu/ms)

### [源码下载](https://github.com/wuxiumu/ms.git)

## 概览
phpms是一款高性能的轻量级PHP框架

遵循 MVC 模式，用于快速开发现代 Web 应用程序

phpms代码简洁优雅，对应用层，数据层，模板渲染层的封装简单易懂，能够快速上手使用

高性能，框架响应时间在1ms以内，单机qps轻松上3000

## 介绍

支持自定义连表，根据项目大小composer可以选择适合自己的数据库框架，phpms默认medoo和pdo两种连接方式

类的自动化加载

api接口路由设计友好 具体可看源码或参考 [phpms框架拓展](https://ms.meiyoufan.com/index.php/index/postinfo/id/36)

框架 Wiki：http://www.phpms.cn

GitHub 地址：https://github.com/wuxiumu/ms

## PHPMS框架
中文最佳实践PHP开源框架,MVC结构的开源PHP框架,composer让php便捷开发成为无限可能。

### [composer中文网](https://www.phpcomposer.com/)
### [composer安装列表](https://packagist.org/)

## 如何启动phpms框架
网站根目录cmd
```
composer update
php -S localhost:8000
```

## 框架目录

```
ms                              [PHP应用目录]
│
├── app                         [模块目录]
│   │
│   ├── ctrl                    [控制器目录]
│   │  
│   ├── model                   [数据模型目录]
│   │   
│   ├── rsa                     [私钥公钥存放目录]│   
│   │ 
│   └── viws                    [视图目录]
│    
├── core                        [PHPMS核心框架目录]
│    │
│    ├── common                 [公共函数目录]
│    │   │
│    │   └──function.php        [自定义公共函数]
│    │
│    ├── config                 [配置目录]
│    │
│    ├── flight                 [flight 引擎目录]
│    │
│    ├── lib                    [驱动目录]
│    │   
│    └── phpmsframe.php         [框架类]
│
├── readme                      [PHPMS框架开发思路和笔记]
│    
└── public                      [公共资源目录]
.gitignore                      [git忽略文件配置]
.htaccess                       [伪静态文件]
api.php                         [api入口文件]  
favicon.ico                     [ico图标] 
index.php                       [后端入口文件]
LICENSE                         [lincese文件]
composer.json                   [composer配置文件]
composer.lock                   [composer lock文件]
README.md                       [readme文件]
w_start_web.bat                 [win下一键启动项目文件] 
```

更多细节请看 [GitHub的PHPMS框架源码](https://github.com/wuxiumu/ms)

## 支持或联系

邮箱：wuxiumu@163.com
