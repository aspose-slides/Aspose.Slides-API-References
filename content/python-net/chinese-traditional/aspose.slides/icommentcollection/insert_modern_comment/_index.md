---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icommentcollection/insert_modern_comment/
weight: 50
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposeslidespointf-datetime}
在指定索引處將新的現代批註插入集合中。

### 返回

已插入的現代批註。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 集合中元素的索引，指示應插入現代批註的位置。 |
| text | **str** | 新現代批註的純文字內容。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要在其中新增現代批註的簡報投影片。 |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | 投影片上與新現代批註關聯的圖形。 |
| position | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 投影片上新增現代批註的位置。 |
| creation_time | **DateTime** | 現代批註建立的時間。 |

### 另見
* 類別 [`ICommentCollection`](/slides/python-net/zh-hant/aspose.slides/icommentcollection)
* 類別 [`IModernComment`](/slides/python-net/zh-hant/aspose.slides/imoderncomment)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)