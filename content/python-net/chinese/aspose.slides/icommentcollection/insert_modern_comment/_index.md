---
title: insert_modern_comment method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icommentcollection/insert_modern_comment/
weight: 50
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposepydrawingpointf-datetime}
在指定索引处向集合插入新的现代评论。

### 返回
已插入的现代评论。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 集合中元素的索引，在该位置应插入现代评论。 |
| text | **str** | 新现代评论的纯文本。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 演示文稿中添加新现代评论的幻灯片。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 幻灯片上与新现代评论关联的形状。 |
| position | **aspose.slides.PointF** | 在幻灯片上添加新现代评论的位置。 |
| creation_time | **DateTime** | 现代评论创建的时间。 |

### 另见
* 类 [`ICommentCollection`](/slides/python-net/zh/aspose.slides/icommentcollection)
* 类 [`IModernComment`](/slides/python-net/zh/aspose.slides/imoderncomment)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)