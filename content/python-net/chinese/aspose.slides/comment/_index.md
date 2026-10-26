---
title: Comment class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/comment/
---
## Comment 类

表示幻灯片上的注释。

The Comment type exposes the following members:

## 属性

| 属性 | 描述 |
| :- | :- |
| [`text`](/slides/python-net/zh/aspose.slides/comment/text/) | 返回或设置幻灯片注释的纯文本。<br/>            读写 **str**. |
| [`created_time`](/slides/python-net/zh/aspose.slides/comment/created_time/) | 返回或设置注释创建的时间。<br/>            将此属性设置为 **System.DateTime** 表示未设置注释时间。<br/>            读写 **System.DateTime**. |
| [`slide`](/slides/python-net/zh/aspose.slides/comment/slide/) | 返回或设置注释的父幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide). |
| [`author`](/slides/python-net/zh/aspose.slides/comment/author/) | 返回注释的作者。<br/>            只读 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh/aspose.slides/comment/position/) | 返回或设置注释在幻灯片上的位置。<br/>            读写 [`PointF`](/slides/python-net/zh/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/zh/aspose.slides/comment/parent_comment/) | 获取或设置父注释。<br/>            读写 [`IComment`](/slides/python-net/zh/aspose.slides/icomment). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/comment/remove/#) | 从父集合中移除该注释及其所有回复。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)