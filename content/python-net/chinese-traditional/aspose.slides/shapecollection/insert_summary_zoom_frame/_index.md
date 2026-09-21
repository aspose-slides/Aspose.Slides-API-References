---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
建立新的 Summary Zoom 框架，並將其插入形狀集合的指定索引位置。

### Returns

新建立的 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe)。

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入 Summary Zoom 框架的零基索引。 |
| x | **float** | 新 Summary Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Summary Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Summary Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Summary Zoom 框架的高度，單位為點。 |

### Remarks

此方法會建立一個 Summary Zoom 框架，彙總簡報中所有章節的摘要連結。

### Exceptions

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果簡報不包含任何章節，或目標投影片不屬於任何章節，則拋出此例外。 |

### See Also
* 類別 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)