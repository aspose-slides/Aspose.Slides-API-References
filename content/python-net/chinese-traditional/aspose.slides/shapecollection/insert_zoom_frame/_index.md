---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
建立一個新的 Zoom 框架，並將其插入至形狀集合中指定的索引位置。

### 傳回值

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標（點）。 |
| y | **float** | 新 Zoom 框架的 y 座標（點）。 |
| width | **float** | 新 Zoom 框架的寬度（點）。 |
| height | **float** | 新 Zoom 框架的高度（點）。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | Zoom 框架參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的投影片不屬於目前的簡報，則拋出此例外。 |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
建立一個帶有預設圖像的新 Zoom 框架，並將其插入至形狀集合中指定的索引位置。

### 傳回值

新建立的 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)。



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 座標（點）。 |
| y | **float** | 新 Zoom 框架的 y 座標（點）。 |
| width | **float** | 新 Zoom 框架的寬度（點）。 |
| height | **float** | 新 Zoom 框架的高度（點）。 |
| slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | Zoom 框架參照的 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 參照投影片 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) 的圖像。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的投影片不屬於目前的簡報，則拋出此例外。 |



### 參見
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`IZoomFrame`](/slides/python-net/zh-hant/aspose.slides/izoomframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)