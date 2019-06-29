---
layout:     post
title:      JavaScript 运行原理
subtitle:   JavaScript 运行原理解析
date:       2019-06-29
author:     MM
header-img: img/react-bg.jpg
catalog: true
tags:
    - JavaScript
---

> 需要提前了解以下概念:

### 目录

  - JS Engine (JS 引擎)
  - Runtime (运行上下文)
  - Call Stake (调用栈)
  - Event Loop (时间循环)
  - Callback (回调)

## JS Engine
 > JS 引擎主要是对js代码进行词法、语法等分析，通过编译器将代码编译成机器可执行的机器码。

 目前流行的JS：V8（开源高性能JS引擎），主要被应用与Chrome，安卓浏览器，node.js等大型项目中。

### 网页渲染流程

![](/img/webkitflow.png)

