---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
在指定索引处向集合插入新评论。

### 返回
已插入的评论。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | index 在集合中的元素位置，comment 将被插入。 |
| text | **str** | 新评论的纯 text。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 演示文稿中用于添加新评论的 slide。 |
| position | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | position 在 slide 上添加新评论的位置。 |
| creation_time | **DateTime** | comment 创建的时间（creation_time）。 |

### 另见
* 类 [`IComment`](/slides/python-net/zh/aspose.slides/icomment)
* 类 [`ICommentCollection`](/slides/python-net/zh/aspose.slides/icommentcollection)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)