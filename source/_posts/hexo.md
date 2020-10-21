---
title: Hexo
date: 2020-08-14 01:37:53
tags:
- hexo
categories:
- 工具
---

> [Hexo](https://hexo.io/zh-cn/docs/) 是一个用于快速搭建博客的框架，使用 Markdown（或其他渲染引擎） 解析文章，快速生成静态网页，同时支持各种主题。

<!-- More -->

## 安装与使用

全局安装：

```
# 安装好后可以全局使用 `hexo` 命令
npm install hexo-cli -g
```

<!-- More | Less -->

查看安装的hexo版本：

```
hexo version
```

初始化博客目录：

```
hexo init [folder]
```

新建文章：

```
# 通过 layout 指定使用 scaffolds 目录下的对应模板
# 省略 layout 的话使用 _config.yml 下的 default_layout
hexo new [layout] <title>
```

生成静态文件：

```
hexo generate [--deploy | -d]
hexo g
```

发布草稿：

```
hexo publish [layout] <filename>
```

启动服务器：

```
# 启动本地服务器，默认为 http://localhost:4000/
hexo server
```

部署网站：

```
# 基于 _config.yml 中 deploy 配置的方式部署生成的静态内容
hexo deploy [--generate | -g]
hexo d
```

清除缓存文件：

```
# 清除缓存文件（db.json）和已生成的静态文件（public）
hexo clean
```

## 几款简约主题推荐

1. [Minos](https://blog.zhangruipeng.me/hexo-theme-minos/) - 简约又好看，支持字数和阅读时长展示
2. [Solar](https://tzvetkov75.github.io/demo_blog/public/home/) - 简约，太阳系动画很不错
3. [Anodyne](http://www.codeblocq.com/assets/projects/hexo-theme-anodyne/) - 简约清爽
4. [LiveMyLife](https://v-vincen.life/tags/) - 简约大气，支持白天/黑夜主题切换
5. [TKL](https://go.kieran.top/)

## 主要需要修改的配置项

## Front-matter

## 资源文件管理