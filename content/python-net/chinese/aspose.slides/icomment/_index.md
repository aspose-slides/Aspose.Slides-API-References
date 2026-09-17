---
title: IComment class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icomment/
---
## IComment 类

表示幻灯片上的评论。

IComment 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`text`](/slides/python-net/zh/aspose.slides/icomment/text/) | 返回或设置幻灯片评论的纯文本。<br/>            读写 **str**. |
| [`created_time`](/slides/python-net/zh/aspose.slides/icomment/created_time/) | 返回或设置评论创建的时间。<br/>            将此属性设置为 **System.DateTime** 表示未设置评论时间。<br/>            读写 **System.DateTime**. |
| [`slide`](/slides/python-net/zh/aspose.slides/icomment/slide/) | 返回或设置评论的父幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide). |
| [`author`](/slides/python-net/zh/aspose.slides/icomment/author/) | 返回评论的作者。<br/>            只读 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh/aspose.slides/icomment/position/) | 返回或设置评论在幻灯片上的位置。<br/>            读写 **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/zh/aspose.slides/icomment/parent_comment/) | 获取或设置父评论。<br/>            读写 [`IComment`](/slides/python-net/zh/aspose.slides/icomment). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/icomment/remove/#) | 从父集合中移除评论及其所有回复。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)