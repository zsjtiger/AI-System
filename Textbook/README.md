<!--Copyright © Microsoft Corporation. All rights reserved.
  适用于[License](https://github.com/YanjieGao/AI-System/blob/main/LICENSE)版权许可-->

# 人工智能系统 教材

本教材的中文名称设定为 **人工智能系统**，主要讲解支持人工智能的计算机系统设计，对应的中英文课程名称为 **人工智能系统** **System for AI**。本课程中将交替使用一下词汇：**人工智能系统**，**AI-System** 和 **System for AI**。

本教材为[微软人工智能教育与共建社区](https://github.com/microsoft/ai-edu)中规划的人工智能相关教材之一，在[A-基础教程](https://github.com/microsoft/ai-edu/tree/master/A-%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B)模块下，课程编号和名称为 *A6-人工智能系统*。

欢迎访问[微软人工智能教育与共建社区](https://github.com/microsoft/ai-edu)的[A-基础教程](https://github.com/microsoft/ai-edu/tree/master/A-%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B)模块访问更多相关内容。

- [人工智能系统 教材](#人工智能系统-教材)
  - [写在前面](#写在前面)
  - [如何浏览本系列教程](#如何浏览本系列教程)
  - [人工智能系统教材设立背景](#人工智能系统教材设立背景)
  - [人工智能系统教材设立目的](#人工智能系统教材设立目的)
  - [人工智能系统教材的设计与特点](#人工智能系统教材的设计与特点)
  - [人工智能系统教材目录与大纲](#人工智能系统教材目录与大纲)
  - [附录](#附录)
  - [反馈与贡献](#反馈与贡献)
  - [写在后面](#写在后面)

## 写在前面

如果您觉得教材对您有帮助，请不要忘记给本站加星（点击网页顶部的Star标签），星越多说明本教材越对大家有帮助，我们就越会努力完善本站。

## 如何浏览本系列教程

1. 如果使用浏览器在线观看的话，可以使用 Edge 或 Chrome 浏览器，[加这个Math展示控件](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima)

2. 也可以clone全部内容到本地，然后用VSCode浏览，但VSCode中需要安装能读取Markdown格式的扩展，比如Markdown AllInOne插件。

3. 本教程提供数据包：在"SourceCode"文件夹中下载"DataDownload.py"并运行，输入本地目录后即可开始下载数据包，并自动解压至当地。


## 人工智能系统教材设立背景

近年来人工智能特别是深度学习技术得到了飞速发展，这背后离不开计算机硬件和软件系统的不断进步。在可见的未来，人工智能技术的发展仍将依赖于计算机系统和人工智能相结合的共同创新模式。需要注意的是，计算机系统现在正以更大的规模和更高的复杂性来赋能于人工智能，这背后不仅需要更多的系统上的创新，更需要系统性的思维和方法论。与此同时，人工智能也反过来为设计复杂系统提供支持。

我们注意到，现在的大部分人工智能相关的教材，特别是深度学习和机器学习相关课程主要集中在相关理论、算法或者应用，与系统相关的教材并不多见。我们希望人工智能系统教材能让人工智能相关教育变得更加全面和深入，以共同促进人工智能与系统交叉人才的培养。


## 人工智能系统教材设立目的

本课程主要为本科生高年级和研究生设计，帮助学生：

1. 完整的了解支持深度学习的计算机系统架构，并通过实际的问题，来学习深度学习完整生命周期下的系统设计。
 
2. 介绍前沿的系统和人工智能相结合的研究工作，包括AI for Systems and Systems for AI，以帮助高年级的本科生和研究生更好的寻找和定义有意义的研究问题。

3. 从系统研究的角度出发设计实验课程。通过操作和应用主流和最新的框架、平台和工具来鼓励学生动手实现和优化系统模块，以提高解决实际问题的能力，而不仅仅是了解工具使用。

**先修课程:** C/C++/Python, 计算机体系结构，算法导论，操作系统，编译原理，计算机网络

## 人工智能系统教材的设计与特点

教材主要包括以下特点：

1. 全面性与体系化: 是人工智能的基础知识和人工智能系统的全栈概述；以及深度学习系统的系统性设计和方法学。

2. 深入浅出: 以易于理解的文字和内容呈现方式，简化的实例，抽象出关键系统问题。同时兼顾当前前沿的研究工作，有一定深度。

3. 启发式思考：问题的定义优先于解决方法，阐述本领域的经典问题和代表性方法。启发读者思考，展开新工作。

4. 兼收并蓄：本教材的设计不仅会借助微软和微软亚洲研究院在人工智能和系统交叉领域的研究成果和经验，其中包括微软及研究院开发的一部分平台和工具，也会参考业界主流经典的人工智能系统工作。教材也鼓励其他学校和老师根据自己的需求添加和调整更多的高级内容，或者其他的实验。

## 人工智能系统教材目录与大纲

- [人工智能系统概述](第1章-人工智能系统概述/1-前言.md) 
  - [深度学习的历史，现状与发展](第1章-人工智能系统概述/1.1-深度学习的历史，现状与发展.md) 	
  - [算法，框架，体系结构与算力的进步](第1章-人工智能系统概述/1.2-算法，框架，体系结构与算力的进步.md) 	
  - [深度学习系统组成与生态](第1章-人工智能系统概述/1.3-深度学习系统组成与生态.md) 

## 附录

- [术语表](术语表.md)

## 反馈与贡献

1. 反馈

    如果您对本模块内容有任何反馈，欢迎在 GitHub [Issues](https://github.com/microsoft/AI-System/issues) 模块中留言，我们会积极了解您的反馈，并尽量满足您的要求。

2. 贡献

    如果您想向本模块提供任何有价值的教程内容，请 fork 本仓库到您自己的账号，编辑内容并提交 Pull Request，我们会及时审阅并处理。

    欢迎向本模块贡献有价值的内容。

## 写在后面

加星点赞是一种良好的Open Source的程序员素养，作者的目标是得到10000颗星！星越多，我们的创作团队越努力！
送人玫瑰，手有余香，传播给你的朋友，让大家一起进步！