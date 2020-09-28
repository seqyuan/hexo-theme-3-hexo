## 关于anno-sc

anno-sc是单细胞大项目兴趣组的博客，我们希望通过博客的形式把单细胞碎片化的知识进行系统化的整理，并且自主的设计展现的空间形式。

> 博客的主要内容是单细胞分析的经验总结、学习笔记的整理以及一些软件分析教程


## 合作更新方式
#### 文章仓库地址

https://github.com/anno-sc/blog_source

#### 合作更新方式

1. 直接在仓库`Add file`，文件以`.md`作为后缀
2. 通过`git`命令行的形式更新仓库文件，新添加的文章以`.md`作为后缀
>  每次 git push之前，请务必先git pull，保证仓库状态最新
3. `Fork`仓库，提交`Pull request`

anno-sc组织的member更新博客可通过前两种方式，其他合作者可通过第三种方式

## 要起的文章格式
文章书写为`markdown`格式，需要在文章开头加入头文件用于生成博客必要的文章分类信息，头文件格式如下：

```
---
title: typora-vue-theme主题介绍
date: 2020-09-25 16:29:00
author: author1
top: true
cover: true
toc: false
summary: 可以为空
categories: Markdown
tags:
  - Typora
  - Markdown
---
```

## 关于文章中的图片 

如果某篇文章中有图片，请在**https://github.com/anno-sc/blog_source/figure/** 中建立独立的文件夹来存放这篇文章的图片，markdown文档中引用的图片路径请以`https://gitee.com/anno-sc/blog_source/raw/master/figure`开头，例如[DC和NK细胞的lineage及marker基因](https://anno-sc.com/2020/09/25/NK_DC_lineage/)这篇文章的图片存放在了这个文件夹内`https://github.com/anno-sc/blog_source/tree/master/figure/DC_marker`，那么这篇文章markdown中的图片链接地址写为：`![](https://gitee.com/anno-sc/blog_source/raw/master/figure/DC_marker/common_lymphoid_progenitors.png)`。

之所以我们图片上传到了`github`，文章图片链接却把前缀改为`gitee`的网址，是因为我们为了保证图片的快速缓冲，建立了两个仓库的自动同步机制。

## 联系我们
有任问题可以github账户登陆本博客的评论系统留言

