---
title: add_zoom_frame method
second_title: Aspose.Slides 適用於 Python via .NET 的 API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
建立一個新的 Zoom 框，並將其加入形狀集合的末端。

### Returns

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Zoom 框的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框的寬度，單位為點。 |
| height | **float** | 新 Zoom 框的高度，單位為點。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 由 Zoom 框參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide);<br/><br/> 必須屬於此簡報。 |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 若參照的投影片不屬於目前的簡報，將拋出此例外。 |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
建立一個新的 Zoom 框，並將其加入形狀集合的末端。

### Returns

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Zoom 框的 x 座標，單位為點。 |
| y | **float** | 新 Zoom 框的 y 座標，單位為點。 |
| width | **float** | 新 Zoom 框的寬度，單位為點。 |
| height | **float** | 新 Zoom 框的高度，單位為點。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 由 Zoom 框參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide);<br/><br/> 必須屬於此簡報。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 參照投影片 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) 的圖像。 |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 若參照的投影片不屬於目前的簡報，將拋出此例外。 |



### See Also
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)