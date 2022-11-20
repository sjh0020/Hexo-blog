---
title: Python+VS Code安装
date: 2022-11-20 16:20:41
tags:
---

# 写在前面
Python是一个优秀的用作自动化的一门编程语言，而VS code则是一个好用的较轻量的代码编辑器，配合插件食用更是能把体验提升一个档次。<br>为防止有人要抬杠说VS code有2~300mb不够轻量，这里我的比较对象是VS(visual studio)这个动辄几十G的玩意，追求轻量级的请百度搜索sublime相关教程。但是[Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus/releases)和[sublime](https://www.sublimetext.com/download)可以作为一个好用的记事本，是时候抛弃Windows系统自带的记事本了「笑」

# 安装Python
这里我选择了先安装Python，方便后面VS code安装插件提示找不到Python路径 (其实影响并不大)
## 下载Python安装包
首先进入[官网](https://www.python.org)，选择Download，直接点击Python3.11.0这个按钮进行下载，或这个[官方下载链接](https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe)进行下载
![Python官网主页面](https://cdn.staticaly.com/gh/sjh0020/picture@master/20221120/Python-HomePage.4sb5epae7mg0.webp)
## 安装Python
找到下载完的文件，双击运行，稍等一会，看到下面的界面就可以开始愉快进行安装啦~
![Python选择安装用户界面](https://cdn.staticaly.com/gh/sjh0020/picture@master/20221117/Python-Setup-select-user.37oqxy3flfu0.webp)
这里选择Customize install（自定义安装）<br>小孩子才做选择，大人全都要:dog:<br>
具体每个选项意思：<br>
第一个就是字面意思的文档啦，必选，方便vs code内查看说明<br>
第二个必选，用于安装库（别人写好的集合了很多方法的文件，可以直接拿来用不用自己从零实现）<br>

![安装文件选项](https://cdn.staticaly.com/gh/sjh0020/picture@master/20221117/Python-Optional-Features.9dju562bv0o.webp)