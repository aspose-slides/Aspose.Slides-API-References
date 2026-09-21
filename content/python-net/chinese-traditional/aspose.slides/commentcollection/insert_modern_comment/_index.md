---
title: insert_modern_comment method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/commentcollection/insert_modern_comment/
weight: 60
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposepydrawingpointf-datetime}
插入新的現代評論至集合中指定的索引位置。

### 返回值

已插入的現代評論。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 集合中元素的索引位置，將在此插入現代評論。 |
| text | **str** | 新現代評論的純文字。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 投影片中要加入新現代評論的 Slide。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 投影片上的 Shape，與新現代評論關聯。 |
| position | **aspose.slides.PointF** | 投影片上要加入新現代評論的位置。 |
| creation_time | **DateTime** | 現代評論建立的時間。 |

### 另請參閱
* 類別 [`CommentCollection`](/slides/python-net/zh-hant/aspose.slides/commentcollection)
* 類別 [`IModernComment`](/slides/python-net/zh-hant/aspose.slides/imoderncomment)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)