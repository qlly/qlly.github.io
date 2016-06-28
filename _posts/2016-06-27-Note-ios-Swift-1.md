---
layout: post
title: "斯坦福大学课程 《Lesson 1：Logistics，iOS8 Overview》"
date: 2016-06-27
excerpt: "斯坦福大学的iOS8+Swift公开课，第一课课堂笔记。"
tags: [Swift, iOS]
comments: true
---

从今天开始会慢慢将自己记录的笔记进行整理。
一方面帮助自己理解记忆，另一方面也希望可以帮到跟我一样从零开始学习的人。编程是一件快乐的事情，希望初学者们不要在还没迈出第一步的时候就被吓到。斯坦福的这个公开课真的讲的很好，并没有一开始就死板地讲述各种数据类型和语法，而是从一个简单的计算器应用开始，一步一步在制作应用的过程中，带入Swift的相关知识。跟着课程，你很快就能制作出自己的第一个app了。如果你还因为害怕英语而犹豫不决，可以参考下面的笔记，跟着说明开始制作app。

# What's in iOS? -- iOS有些什么？简述iOS的四层结构

iOS整个系统的架构由下面的四层构成。进行iOS的开发，首先应从最上层（Cocoa Touch）开始入手，当需要进行多媒体的处理时，再往下层去寻找相关的构架来实现所需的功能。

### 1）Cocoa Touch

iOS的最上层，应用程序界面上的各种组件都是由它来提供的。而且还负责与用户的交互操作，例如处理屏幕上的多点触摸事件，文字图片的显示，文件的存取等等。

<figure>
    <img src="/assets/img/iOS-Lesson1/1.png">
</figure>

### 2）Media

媒体层，主要提供图形，音频，视频等多媒体功能。

<figure>
    <img src="/assets/img/iOS-Lesson1/2.png">
</figure>

### 3）Core Services

Core Services包含了Foundation.Framework和Core Foundation.Framework。提供了处理字符串，时间日历等基本功能，另外还提供安全性管理，GPS定位等其他功能。

<figure>
    <img src="/assets/img/iOS-Lesson1/3.png">
</figure>

### 4）Core OS

Core OS是最底层，包含了iOS的一些基础功能，例如硬件驱动，内存管理，网络等等。

<figure>
    <img src="/assets/img/iOS-Lesson1/4.png">
</figure>

# Platform Components -- 开发中需要什么？开发平台组成

工具：Xcode <br>
语言：Swift，Objective-C （课程中使用Swift）<br>
框架：Foundation（基础功能），UIkit（UI界面），Core Data，Map Kit等等 <br>
设计模式：MVC（将应用程序分成三个核心部件：Model 模型，View 视图，Controller 控制器）<br>

<figure>
    <img src="/assets/img/iOS-Lesson1/5.png">
</figure>

# Demo -- 制作一个计算器

<figure>
    <img src="/assets/img/iOS-Lesson1/6.png">
</figure>

### 通过Demo可以学习：
·在Xcode中建立一个项目
·制作UI，并使它自适应画面
·使用iOS Simulator
·使用‘println’指令（新版修改为‘print’）
·用Swift定义一个class（类）
·建立UI组件和Swift代码中变量的联系
·建立UI组件和Swift代码中函数的联系
·从代码查看iOS帮助文档
·Optional类型

### 步骤

1）打开Xcode，新建一个项目

<figure>
    <img src="/assets/img/iOS-Lesson1/7.png">
</figure>

<figure>
    <img src="/assets/img/iOS-Lesson1/8.png">
</figure>

<figure>
    <img src="/assets/img/iOS-Lesson1/9.png">
</figure>

<figure>
    <img src="/assets/img/iOS-Lesson1/10.png">
</figure>

项目创建成功后，会出现如下画面。<br>

<figure>
    <img src="/assets/img/iOS-Lesson1/11.png">
</figure>

2）编辑应用界面

<figure>
    <img src="/assets/img/iOS-Lesson1/12.png">
</figure>




