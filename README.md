# TheNextGreatProject
这里是关于整个项目的说明

## How we work

该项目由任意“姬本法”成员参与。无组织，无计划，各位根据自己的步调自由参与。欢迎任意水平的人随意参与（你就算只会个if也行），本项目的宗旨并非构建我们的团购网站，而是希望各位以各位自己的个人成长为中心，使用各位自己的方式来参与。也就是说，轴心在各位自己的身上，而不是在项目身上。

该项目采用类似开源贡献的方式（然而并没有开源，我并没有设置开源协议），各位根据自己的进度来参与。具体的参与方式是：

1. 在jihezhi组织下创建自己的repository，构建自己的内容（比如说，你决定参与前端，那么你开一个名字能够让我明白是你的repository，在下面贡献你自己的HTML代码）。我会定期点评各位的代码，提出指导，以及如果合适，将代码merge进我们的FrontEnd repository中。

2. 对已经merge的FrontEnd repository和BackEnd repository，各位可以按照传统的开源贡献方式提交经过修改的代码。

## What to do

该项目的目标是构建我们的团购网站在线服务系统。网站由前端和后端两部分组成，前端使用AngularDart框架，后端使用Go和MySql。

### 什么是前端和后端？

一个网站由前端和后端构成。前端，是指网站呈现给用户的部分，即直接和用户交互的这个网页。诚然，对于一个静态的HTML（即看起来就是一篇文章，除了字什么都没有）的简单网页而言，没什么可值得编程的。然而现代网站的网页都十分复杂，需要我们在前端进行大量编程。比如说，我们的网站会需要处理用户的各种点击事件，比如罗列产品、查看产品详情、加入购物车等等。这些都是前端的程序所实现的。

前端程序的执行是用户的浏览器（即Chrome）完成的。一般都使用JavaScript，然而我们采用最尖端的新语言Dart 2。小白也不用怕，掌握Dart 2你并不需要先掌握JavaScript。

前端程序会将部分数据根据IP地址送到后端，即我们的后台服务器。后端会处理这些数据（比如说，接受前端送来的订单数据）后将结果返回前端，前端处理后呈现给用户。

#### 前端

具体的教程汇总会出现在FrontEnd和BackEnd repository下（各位可以边学习边练手）。这里是任务描述。

我们的前端的核心任务是为用户提供一个类似 www.bulletproof.com 这样或者淘宝、京东那样的购物界面。我们将商品像防弹官网那样罗列出来，用户点击后可以查看详情。大家可以看看防弹官网的设计作为参考。

我们并不需要完全照搬防弹官网，各位可以根据自己的感觉随意设计，无论是结构还是设计都可以随意设计。你可以按照你理想中的样子设计我们的团购网站的网页和功能。

如果你不知道该如何入手，你是0基础，可以通过这样的顺序来：

1.学习HTML5

2.使用HTML5构建一个差不多的静态网页

3.学习CSS3

4.使用HTML5+CSS3构建一个好看的静态网页

5.学习JavaScript来学习如何让网页实现交互

6.学习Bootstrap来了解现代工业如何快速生产好看的网页（我们不会使用Bootstrap）

7.学习Dart 2来替代JavaScript

8.学习AngularDart来了解如何使用现代工业框架构建网站

9.使用AngularDart来实际参与我们的项目

#### 后端

后端负责处理前端发过来的各种请求，比如说前端可能送来一个表单，上面写着“用户：和泉纱雾 商品名称：BOO 商品数量：100”，后端需要将这个数据处理后存入数据库，并且返回一些回应，比如说返回“订单处理成功”或者“你怎么买这么多？是不是点错了?”之类的。后端的程序运行在服务器上，服务器一般是Linux系统的某个分支（我们使用CentOS）。你可以按照你的想象随意设计API（即你想要让服务器接收什么，返回什么）。

如果你不知道如何入手，可以通过这样的顺序：

1.学习Go语言

2.在自己的电脑上使用Go语言写一些自己喜欢的小程序

3.在自己的电脑上使用Go语言搭建一些服务器

4.学习数据库，在自己的电脑上玩玩MySql

5.实际参与我们的项目建设

## When to finish

虽然各位步调任意，但大家也知道我们这个项目小伙伴们也希望早日上线，所以我自己也会贡献代码（根据各位的速度，比如说各位太慢我可能就会以自己写为主；各位贡献得多我就会以组织为主），如果各位没什么进展项目就完成了，那大家学到的东西就会很少。所以希望各位能够拿出时间来投入（主要是为了各位的成长）！
