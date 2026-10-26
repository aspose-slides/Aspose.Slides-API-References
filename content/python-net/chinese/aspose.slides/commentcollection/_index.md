---
title: CommentCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentcollection/
---
## CommentCollection 类

表示单个作者的评论集合。

CommentCollection 类型公开以下成员：

获取指定索引处的元素。  
只读 [`Comment`](/slides/python-net/zh/aspose.slides/comment)。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/commentcollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/commentcollection/to_array/#) | 创建并返回包含所有评论的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/commentcollection/to_array/#int-int) | 创建并返回包含指定范围内所有评论的数组。 |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/zh/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | 在集合末尾添加新评论。 |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/zh/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | 在集合末尾添加新现代评论。 |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/zh/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | 在指定索引处向集合插入新评论。 |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/zh/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | 在指定索引处向集合插入新现代评论。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/commentcollection/remove_at/#int) | 移除集合中指定索引处的元素。 |
| [`remove(self, comment)`](/slides/python-net/zh/aspose.slides/commentcollection/remove/#icomment) | 移除集合中指定评论的第一次出现。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/commentcollection/clear/#) | 移除集合中的所有评论。 |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/zh/aspose.slides/commentcollection/find_comment_by_idx/#int) | 通过索引在集合中查找评论。 |

### 参见
* 类 [`Comment`](/slides/python-net/zh/aspose.slides/comment)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)