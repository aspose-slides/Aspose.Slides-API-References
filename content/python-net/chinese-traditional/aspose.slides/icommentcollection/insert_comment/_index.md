---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 參考手冊
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
在集合中指定的索引位置插入新評論。

### 返回值

已插入的評論。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 集合中應插入評論的元素索引。 |
| text | **str** | 新評論的純文字內容。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要在其上新增評論的投影片。 |
| position | **aspose.slides.PointF** | 在投影片上新增評論的位置。 |
| creation_time | **DateTime** | 評論建立的時間。 |

### 另請參閱
* 類別 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)
* 類別 [`ICommentCollection`](/slides/python-net/zh-hant/aspose.slides/icommentcollection)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)