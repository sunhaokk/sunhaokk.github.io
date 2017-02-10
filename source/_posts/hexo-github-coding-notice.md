---
title: hexo部署到github和coding注意事项
date: 2017-01-11 15:10:57
tags:
---


1. 在github新建项目的时候一定输入的是youname.github.io其中youname是你的用户名。
因为github默认的页面，就是你的用户名。所以这个不要乱改。
![](http://ojlt0g866.bkt.clouddn.com/da-png-githubproject.png)
1. 同理coding在新建项目的时候一定也要是youname。你的用户名。coding默认也是用户名即是主页，否则生成的页面地址是http://youname_.coding.me/youproject。
![](http://ojlt0g866.bkt.clouddn.com/da-png-codingreg.png)

1. 在hexo的配置文件_config.yml中，因为yml要求规范严格，所以一定要注意缩进和空格。
```
deploy:
  type: git
  repo: 
	github: git@github.com:youname/youname.github.io.git
	coding: git@git.coding.net:youname/youname.git
  branch: master
```
![](http://ojlt0g866.bkt.clouddn.com/da-png-watch.png)

	
