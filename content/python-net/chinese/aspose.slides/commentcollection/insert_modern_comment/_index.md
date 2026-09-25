---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/commentcollection/insert_modern_comment/
weight: 60
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposeslidespointf-datetime}
在指定索引处向集合插入新的现代评论。

### 返回

已插入的现代评论。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 集合中应插入现代评论的元素索引。 |
| text | **str** | 新现代评论的纯文本。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 演示文稿中添加新现代评论的幻灯片。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 与新现代评论关联的幻灯片上的形状。 |
| position | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 在幻灯片上添加新现代评论的位置。 |
| creation_time | **DateTime** | 现代评论创建的时间。 |

### 另请参见
* 类 [`CommentCollection`](/slides/python-net/zh/aspose.slides/commentcollection)
* 类 [`IModernComment`](/slides/python-net/zh/aspose.slides/imoderncomment)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)