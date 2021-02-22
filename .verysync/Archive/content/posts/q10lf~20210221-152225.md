---
title: "我从 Ranger 换到了 lf"
date: 2021-02-20T21:54:26+08:00
draft: flase
tags: [Linux]
---

## 起因

我想不会有谁用得好好的突然想换用其他软件，我也不例外。

那天我启动 Ranger ，突然弹出的满屏日志令人头大，我又不能放下手头的东西去处理它，幸好，同样在终端下用来管理文件的应用还有很多。
![ranger](https://thaoeu.site/q10lf/Q07'21-1257ranger.png)

目光转向 lf ，拿它作比较并不代表 Ranger 不好，相反，我仍使用 Ranger 。

## 优点

1. 速度

这里用一台从未安装过 Ranger 及 lf 的云服务器做实验，以保证两者均处于*全新* 的状态。

两者均采用 yay 安装。
![vps](https://thaoeu.site/q10lf/Q07'21-1011.pnglf.png)

可以看出 lf 的启动速度较 Ranger 有很大优势，这一点在低配电脑体现更明显，一方面是 Go 语言运行速度优势，另一方面 Ranger 的功能和体积都比 lf 大。

2. 全局性

在未配置、添加插件的情况下，lf 可以在多个终端间进行文件操作，而 Ranger 各终端间相互独立。
![ranger](https://thaoeu.site/q10lf/Q07'21-0530.pngranger2.png)
![lf](https://thaoeu.site/q10lf/Q07'21-0530.pngranger2.png)

## 缺点

lf 无法预览图片！尝试了各种方法均无功而返，如果有好方法请告知我。
![图片预览](https://thaoeu.site/q10lf/Q07'21-2231.pngrage2lf.png)

