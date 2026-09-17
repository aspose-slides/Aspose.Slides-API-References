---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
在指定索引处向集合插入新评论。

### 返回

已插入的评论。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 在集合中要插入评论的元素的索引。 |
| text | **str** | 新评论的纯文本。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 演示文稿中要添加新评论的幻灯片。 |
| position | **aspose.slides.PointF** | 在幻灯片上添加新评论的位置。 |
| creation_time | **DateTime** | 评论创建的时间。 |



### 另请参阅
* 类 [`CommentCollection`](/slides/python-net/zh/aspose.slides/commentcollection)
* 类 [`IComment`](/slides/python-net/zh/aspose.slides/icomment)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)