---
title: "Hugo学习笔记"
description: 
date: 2024-09-23T21:36:32+08:00
image: 
math: 
license: 
hidden: false
comments: true
draft:
---
# Hugo图片存储问题

由于渲染后的文件建构与原本放在content中post的文件结构不一样，因此会导致直接在VScode中粘贴图片，渲染后的博客无法显示图片，解决方法有以下三种

1. 图片放在根目录/static/img下，引用方式为"\!\[\](/img/1727101461771.png\)" 通过这种方式引用图片，但是这种方式会导致图片无法在本地预览，而且操作繁琐
2. 图床引用，将图片上传到图床，通过图床链接引用图片(学习中ing)
