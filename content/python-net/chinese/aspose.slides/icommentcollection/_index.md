---
title: ICommentCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/
---
## ICommentCollection 类

表示单个作者的评论集合。

ICommentCollection 类型公开以下成员：

获取指定索引处的元素。
            只读 [`IComment`](/slides/python-net/zh/aspose.slides/icomment).

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/icommentcollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/icommentcollection/to_array/#) | 创建并返回包含所有评论的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/icommentcollection/to_array/#int-int) | 创建并返回指定范围内所有评论的数组。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | 在集合末尾添加新评论。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | 在集合末尾添加新的现代评论。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | 在指定索引处向集合插入新评论。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | 在指定索引处向集合插入新的现代评论。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/icommentcollection/remove_at/#int) | 删除集合中指定索引处的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh/aspose.slides/icommentcollection/remove/#icomment) | 删除集合中指定评论的第一次出现。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/icommentcollection/clear/#) | 删除集合中的所有评论。 |

### 参见
* 类 [`IComment`](/slides/python-net/zh/aspose.slides/icomment)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)