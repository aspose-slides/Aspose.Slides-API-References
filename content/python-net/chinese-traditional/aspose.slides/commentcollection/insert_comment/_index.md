---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 參考手冊
description: 
type: docs
url: /zh-hant/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
在指定索引處將新評論插入集合。

### 返回
已插入的評論。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 集合中應插入評論的元素索引。 |
| text | **str** | 新評論的純文字。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 在簡報中加入新評論的投影片。 |
| position | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 在投影片上新增評論的位置。 |
| creation_time | **DateTime** | 評論建立的時間。 |

### 另見
* 類別 [`CommentCollection`](/slides/python-net/zh-hant/aspose.slides/commentcollection)
* 類別 [`IComment`](/slides/python-net/zh-hant/aspose.slides/icomment)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)