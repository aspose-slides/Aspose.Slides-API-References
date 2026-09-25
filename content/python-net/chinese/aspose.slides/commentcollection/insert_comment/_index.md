---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentcollection/insert_comment/
weight: 50
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
| index | **int** | 集合中元素的索引，表示应在此处插入评论。 |
| text | **str** | 新评论的纯文本。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 演示文稿中添加新评论的幻灯片。 |
| position | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 幻灯片上添加新评论的位置。 |
| creation_time | **DateTime** | 评论创建的时间。 |

### 另见
* 类 [`CommentCollection`](/slides/python-net/zh/aspose.slides/commentcollection)
* 类 [`IComment`](/slides/python-net/zh/aspose.slides/icomment)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)