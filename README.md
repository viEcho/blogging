# blogging
下载项目后，最好去hexo官网阅读下官方文档；

本项目为前期调试项目，目的为wordpress搭建的博客主题niRvana主题移值到hexo做适配
<a href="https://github.com/michaelliunsky/niRvana-theme">niRvana主题对应的博客网站：https://blog.mkliu.top </a>

## 本地启动
cd blogging
npm install
hexo clean
hexo g
hexo s
访问4000端口对应本地启动地址

## 其他
其它npm问题请自行百度解决，例如全局安装；设置淘宝镜像等；需注意nodejs 升级到最新版本

## 准备工作
了解ejs语法，了解php语法；这样便于理解对应的布局及函数交互，便于理解如何将php写的页面如何用ejs语法重写


## 项目已拉了landscape 及 redefine主题
可自行在最外层_config.yml文件中替换对应的主题名，启动看不同的效果；以及页面调试，或者你本地可以启三个不同主题下的代码便于查看不同主题下的样式；
hexo s -p 80 将用指定端口启动