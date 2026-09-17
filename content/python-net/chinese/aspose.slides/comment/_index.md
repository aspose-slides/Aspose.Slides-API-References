---
title: Comment class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/comment/
---
## Comment 类

表示幻灯片上的评论。

Comment 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/zh/aspose.slides/comment/text/) | 返回或设置幻灯片评论的纯文本。<br/>            读/写 **str**. |
| [`created_time`](/slides/python-net/zh/aspose.slides/comment/created_time/) | 返回或设置评论创建的时间。<br/>            将此属性设置为 **System.DateTime** 表示未设置评论时间。<br/>            读/写 **System.DateTime**. |
| [`slide`](/slides/python-net/zh/aspose.slides/comment/slide/) | 返回或设置评论的父幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide). |
| [`author`](/slides/python-net/zh/aspose.slides/comment/author/) | 返回评论的作者。<br/>            只读 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh/aspose.slides/comment/position/) | 返回或设置评论在幻灯片上的位置。<br/>            读/写 **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/zh/aspose.slides/comment/parent_comment/) | 获取或设置父评论。<br/>            读/写 [`IComment`](/slides/python-net/zh/aspose.slides/icomment). |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/comment/remove/#) | 从父集合中移除评论及其所有回复。 |

### 另见
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)