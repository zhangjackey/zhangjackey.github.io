---
title: PostgreSQL优化器白话(10) - 我再补充两句
date: 2020-10-03 09:13:44
tags:
---


**全文目录**

1. {% post_link postgresql-optimizer-outline-1 《PostgreSQL优化器白话》- 为什么优化 %}
2. {% post_link postgresql-optimizer-outline-2 《PostgreSQL优化器白话》- SQL进化史 %}
3. {% post_link postgresql-optimizer-outline-3 《PostgreSQL优化器白话》- 提升！提升！ %}
4. {% post_link postgresql-optimizer-outline-4 《PostgreSQL优化器白话》- 下推！下推！ %}
5. {% post_link postgresql-optimizer-outline-5 《PostgreSQL优化器白话》- 严格要求自己 %}
6. {% post_link postgresql-optimizer-outline-6 《PostgreSQL优化器白话》- 统计局旁的泉水 %}
7. {% post_link postgresql-optimizer-outline-7 《PostgreSQL优化器白话》- 你走你的阳关道 %}
8. {% post_link postgresql-optimizer-outline-8 《PostgreSQL优化器白话》- 算计不到就受穷 %}
9. {% post_link postgresql-optimizer-outline-9 《PostgreSQL优化器白话》- 找饭店 %}

《PostgreSQL优化器白话》暂时剧终了，我们基本上涵盖了大部分查询优化的概念，但是由于篇幅比较小，没有把细节说得特别到位，其中有大部分内容是摘抄自《PostgreSQL技术内幕：查询优化深度探索》一书的概念解释的部分，然后以小明、大明和牛二哥进行对话的方式展现出来，对于书中介绍的代码分析的部分以及比较深入的实现细节，由于不太容易通过对话的方式展示，所以在《PostgreSQL优化器白话》中没有涉及到。

我已经尽我所能将这种对话的形式写的具有故事性一些，但是限于作者的语言能力，有些情节的切换上会显得比较生硬，在情节的处理上有时也相对比较单薄了，不过请放心，我即使再努力也写不出来世界名著，所以请不要鄙视我，因为我生气起来连我自己都害怕。