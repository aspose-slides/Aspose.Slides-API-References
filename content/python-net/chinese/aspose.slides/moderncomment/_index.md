---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/moderncomment/
---
## ModernComment 类

表示幻灯片上的评论。

**继承：**[`ModernComment`](/slides/python-net/zh/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/zh/aspose.slides/comment)

ModernComment 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/zh/aspose.slides/moderncomment/text/) | 返回或设置幻灯片评论的纯文本。<br/>            读/写 **str**. |
| [`created_time`](/slides/python-net/zh/aspose.slides/moderncomment/created_time/) | 返回或设置评论创建的时间。<br/>            将此属性设置为 **System.DateTime** 表示未设置评论时间。<br/>            读/写 **System.DateTime**. |
| [`slide`](/slides/python-net/zh/aspose.slides/moderncomment/slide/) | 返回或设置评论的父幻灯片。<br/>            只读 [`ISlide`](/slides/python-net/zh/aspose.slides/islide). |
| [`author`](/slides/python-net/zh/aspose.slides/moderncomment/author/) | 返回评论的作者。<br/>            只读 [`ICommentAuthor`](/slides/python-net/zh/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/zh/aspose.slides/moderncomment/position/) | 返回或设置评论在幻灯片上的位置。<br/>            读/写 [`PointF`](/slides/python-net/zh/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/zh/aspose.slides/moderncomment/parent_comment/) | 获取或设置父评论。<br/>            读/写 [`IComment`](/slides/python-net/zh/aspose.slides/icomment). |
| [`shape`](/slides/python-net/zh/aspose.slides/moderncomment/shape/) | 返回与评论关联的形状。<br/>            只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/zh/aspose.slides/moderncomment/text_selection_start/) | 获取或设置文本框中选择文本的起始位置（如果评论与 AutoShape 关联）。<br/>            读/写 **int**. |
| [`text_selection_length`](/slides/python-net/zh/aspose.slides/moderncomment/text_selection_length/) | 获取或设置文本框中选择文本的长度（如果评论与 AutoShape 关联）。<br/>            读/写 **int**. |
| [`status`](/slides/python-net/zh/aspose.slides/moderncomment/status/) | 获取或设置评论的状态。<br/>            读/写 [`ModernCommentStatus`](/slides/python-net/zh/aspose.slides/moderncommentstatus). |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides/moderncomment/remove/#) | 从父集合中删除评论及其所有回复。 |

### 另请参阅
* 类 [`Comment`](/slides/python-net/zh/aspose.slides/comment)
* 类 [`ModernComment`](/slides/python-net/zh/aspose.slides/moderncomment)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)