---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/insert_modern_comment/
weight: 50
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposeslidespointf-datetime}
在指定索引处向集合中插入新的现代评论。

### Returns

已插入的现代评论。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index of the element in a collection at which modern comment should be inserted. |
| text | **str** | Plain text of a new modern comment. |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | Position on a slide where to add a new modern comment. |
| creation_time | **DateTime** | Time of a modern comment creation. |

### See Also
* 类 [`ICommentCollection`](/slides/python-net/zh/aspose.slides/icommentcollection)
* 类 [`IModernComment`](/slides/python-net/zh/aspose.slides/imoderncomment)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)