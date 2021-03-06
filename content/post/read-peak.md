---
title: "关于编程的练习方法——读《刻意练习》有感"
date: 2017-10-21T14:03:06+08:00
lastmod: 2017-10-26T14:03:06+08:00
# draft: true
keywords: ["刻意练习"]
description: ""
tags: ["练习"]
categories: ["阅读"]
# author: ""
# comment: false
# toc: false
contentCopyright: false
reward: false
mathjax: false
---
![](https://img3.doubanio.com/lpic/s29105145.jpg)

豆瓣链接：[刻意练习 (豆瓣)](https://book.douban.com/subject/26895993/)



这是这样的一本书：知道如何练习的人觉得此书在说一些废话，而遇到瓶颈停滞不前的人会觉得好像突然开了窍。我就是后者，这本书对我个人而言在练习方法上的启发是巨大的。两个多月前，我读完了这本书，这两个多月，我运用此书中得到的启发练习编程，感受到了明显的进步。这篇读后感，算是对写作的练习，也算是对自己的启发做个总结。

<!--more-->

主要有以下几条：

1. 练习目的一定要明确
2. 一定要有反馈
3. 通过练习不断重构心理表征
4. 专注也可以练习




## 明确练习目的
在没有阅读此书之前，我对「练习」并没有那么重视。这可能与我的「自信」，以及经常试图消化更多知识有一定关系。从2011年开始，我断断续续一直在学习编程，但至今只能写一些短小的程序，甚至连基本的标准库都没能完全熟悉。我会写程序吗？我只是大概知道了程序是怎么一回事儿，知道了它的基本语法，能看懂一些比较短的代码，会使用一些框架api，而已。我感觉自己一直在原地打转，也因此有好几次遇到瓶颈后中断了学习。唯一庆幸的是，编程是我的乐趣，我始终都还保持着学习编程的动机。

认清自己的技能水平并不容易。很多时候，通过google搜索，然后复制黏贴，自以为解决了问题就算掌握了，而实际上只是个代码搬运工而已，当自己写的时候还是不会写。就像看了很多书、很多教程，以为懂了，实际上依然不知道该如何运用。我必须认清事实，我的编程技能水平还很低，我的基础很薄弱，我的练习太少了。我告诉自己，不要试图一口吃下一整个馒头，不要试图同时追两只兔子。

我最近在学习JavaScript，为了提升水平，我在网上找练习题来做，机缘巧合就找到了 [codewars][] 这个网站，它完全符合我目前的需要，并且也完全符合刻意练习的要求（有非常好的反馈机制）。我给自己制订了计划，每天完成5道练习，每周对练习进行总结。最初的目标也非常简单：提高 [codewars][] 上的等级。我现在的等级是 **5kyu** （最高等级 1kyu，最低等级 8kyu），与游戏中打怪练级相似，升级的过程，也是动机的来源，等级越高难度越大。

我在练习的过程中，不断增添新目标，比如以下几个小目标：

1. 熟悉JS 语法
2. 熟悉ES6新增的语法
3. 熟悉JS标准库

这几个小目标我目前基本完成了。

## 没有反馈的练习是无效的

我在《刻意练习》这本书中得到的一点很重要的启发是：没有反馈的练习是无效的。

当你写完一段代码，如何能够判断它的好坏？首先，能够运行是最基本的要求，也是最直接的反馈。但你个人很难判断它是否是最优解，很难判断它是否写的漂亮。如果有一位专家在旁边给你修正建议，那无疑是最好的反馈。但是作为自学者，很多时候根本没有人教你。我在网上看到有人给的建议是，将写的代码上传到github，问题是开源的代码太多了，根本没人关注你，没人给你提意见，你只是一个人（但对有一定开发能力的程序员来说，这其实是一个很好的获得反馈的方式，只是目前还不适合我）。还有人建议，参与开源项目的开发，为开源项目改bug贡献代码，这也是获得反馈的好方法，前提是要先找到合适的开源项目，这需要机缘（有很多不错的开源项目已经非常完善了，想要参与需要一定的编程功底），它可能是你现在正在使用的某个软件。

回到 [codewars][] 。[codewars][] 上最大的优点是：它有一个非常好的 **反馈机制** 。每当我完成一个练习，它会给出投票数最高、以及最聪明的解答。通过参考「牛人」的解答，让我学习到了很多编程套路，还有标准库的巧妙用法，以及漂亮的代码该有的样子。

我总结一下几点经验：

1. 先独立完成习题，完成后看最佳答案是如何完成的，与自己的答案进行对比。
2. 多关注一些牛人，看他们是如何解答的。（等级排名前50的我全部关注了）
3. 重复，直到掌握了那个技巧 。
4. 针对某一个知识点，强化训练。
5. 总结并复习。


### 怎样针对某一个知识点进行强化训练？

我的方法是，在google 上搜 "codewars collection" ，这样可以搜索到其他用户针对某一类型的习题做的收藏。比如下面这个链接的收藏分类非常的清楚 https://www.codewars.com/users/juansgaitan/authored_collections （Generator， Functional， Recursion， RegEx 等等）。

### 制造竞争  加入组织

一个小技巧，在 [codewars][] 的个人资料里设置你的 **Clan** (相当于一个组织)，比如我设置的 "China"，这样相同组织里的所有人都将成为 Allies ，你可以看到他们的等级以及 Honor 值。在同一个组织中，超过你的 Allies ，这不也是答题的动力吗？

![read-peak](http://o7faub01q.bkt.clouddn.com/images/readread-peak.png)



## 通过练习不断重构心理表征
什么是心理表征（Mental representations）？要解释这个专业术语不太容易，你可以阅读一下下面几个链接：

- [认知心理学中「表征」的概念是什么？ - 知乎](https://www.zhihu.com/question/21000475)
- [Mental representation - Wikipedia](https://en.wikipedia.org/wiki/Mental_representation)
- [Peak: Secrets from the New Science of Expertise by Anders Ericsson and Robert Pool — Elizabeth Floyd](https://www.elizabethfloyd.com/blog/2016/09/30/peak-by-anders-ericsson-and-robert-pool)



书中是这么说的：

{{< blockquote >}}

"心理表征是一种与我们大脑正在思考的某个物体、某个观点、某些信息或者其他任何事物相对应的心理结构，或具体或抽象"

{{< /blockquote >}}

{{< blockquote >}}

"将杰出人物和我们其他人区分开来的主要因素是：他们经过年复一年的练习，已经改变了大脑中的神经回路，以创建高度专业化的心理表征，这些心理表征反过来使得令人难以置信的记忆、规律的识别、问题的解决等成为可能，也使得他们能够培养和发展各种高级的能力，以便在特定的专业领域中表现卓越。"

{{< /blockquote >}}




（题外话：我个人觉得把 "Mental representation" 翻译成「认知表征」更合适。）

那么，知道了这个「心理表征」有什么用？它解释了为什么我们能够通过刻意练习提升水平。当我们习惯了在舒适区中思考，在舒适区中解决问题，我们自然而然就形成了一套认知，这套认知在应对舒适区内的情况能够得心应手，而一旦超越舒适区就会变得没那么容易。这就能说明刻意练习的目的：提升认知水平，从而应对更复杂更棘手的局面。

在这个信息、资源如此充分的时代，我们很容易产生一个幻觉，就是自以为知道的很多。通过google搜索我们可以解决一系列问题，好像都不必思考了，google一下就有答案。现实是，通过google 能解决的都是一个个具体的小问题，它无法代替我们思考，无法代替我们面对复杂的局面做出合理的决策。

从另外一个角度讲，这本书重构了我的认知。但是，如果我对此就感到满足了的话，那么我的认知水平也就仅限于此了。



## 专注也可以练习

这本书中不断有提到 **专注** 这两个字。作者说：

{{< blockquote >}}

「有目的的练习是专注的」，「要以专注的方式制订明确的目标」

{{</blockquote >}}

{{< blockquote >}}

「为了在没有导师的时候有效地练习某种技能，牢牢记住以下三个F，将是有帮助的。这三个F，其实是以字母F开头三个单词，即：专注（focus）、反馈（feedback）以及纠正（fix it）」。

{{< /blockquote >}}

怎样能够保持专注？作者给的建议是保持动机，但拥有了强烈的动机就能不断保持专注了吗？我对此持怀疑态度。很多时候，无法专注就是无法专注，各种各样的杂念在脑海中飘来飘去，一会儿看下微信，一会儿看看网页，很难一心一意的专注于手头的事情。

直到我阅读了《正念的奇迹》这本书，结合《刻意练习》，我意识到 **专注** 也是可以练习的。举个例子，在你做你不喜欢做的事情，比如有一大堆的碗要洗，或者要修改别人丑陋的代码，你会不会感到烦躁？你会不会想很多别的事情？当你有各种各样的杂念的时候，你很难去保持专注。

关于《正念的奇迹》，关于怎样练习专注，我想另外写一篇文章，再谈一谈它对我的启发。




## 还没有结束

作者在书中质疑了天才，强调了普通人只要找到合适的方法（问题是如果没有一位好的老师指点，我们怎么知道方法是否合适呢？）通过大量刻苦刻意的练习，也能够达到天才的水平。这碗鸡汤我先喝了。毕竟在这个互联网时代，很多领域的练习方法都有现成的，就比如编程，只要沿着前人铺好的路走下去，至少说是能够达到职业水准吧。如果你还没有比别人付出更大的努力，你怎么知道自己不行呢？理论知道的再多再清楚，终究是要回归实践的，更何况这本书讲的就是练习，那就少说废话、好好练习去吧！



[codewars]: http://www.codewars.com/r/nTMAyg
