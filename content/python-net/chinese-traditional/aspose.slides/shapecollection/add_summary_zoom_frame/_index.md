---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
建立一個新的 Summary Zoom 框架，並將其新增到形狀集合的末尾。

### Returns

新建立的 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Summary Zoom 框架的 x 座標，單位為點。 |
| y | **float** | 新 Summary Zoom 框架的 y 座標，單位為點。 |
| width | **float** | 新 Summary Zoom 框架的寬度，單位為點。 |
| height | **float** | 新 Summary Zoom 框架的高度，單位為點。 |

### Remarks

此方法會建立一個新的 Summary Zoom，並將所有投影片中各節的物件集合放入其中。

### Exceptions

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果簡報中沒有任何節，或目標投影片不屬於任何節，則拋出此例外。 |

### See Also
* 類別 [`ISummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isummaryzoomframe)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)