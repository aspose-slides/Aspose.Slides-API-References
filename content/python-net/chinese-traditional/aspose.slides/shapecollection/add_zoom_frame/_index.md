---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
建立一個新的 Zoom 框架，並將其加入到形狀集合的末尾。

### 返回

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Zoom 框架的高度，以點為單位。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | Zoom 框架所參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide);<br/><br/>必須屬於此簡報。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的投影片不屬於目前的簡報，則拋出此例外。 |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
建立一個新的 Zoom 框架，並將其加入到形狀集合的末尾。

### 返回

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Zoom 框架的高度，以點為單位。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | Zoom 框架所參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide);<br/><br/>必須屬於此簡報。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 參照投影片 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) 的影像。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的投影片不屬於目前的簡報，則拋出此例外。 |

### 另請參閱
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)