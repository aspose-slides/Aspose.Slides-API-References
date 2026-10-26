---
title: add_section_zoom_frame method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
建立一個新的 Section Zoom 框架，並將其新增至圖形集合的末端。

### 回傳

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 座標（單位：點）。 |
| y | **float** | 新 Section Zoom 框架的 y 座標（單位：點）。 |
| width | **float** | 新 Section Zoom 框架的寬度（單位：點）。 |
| height | **float** | 新 Section Zoom 框架的高度（單位：點）。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)；<br/><br/>必須屬於此簡報且至少包含一張投影片。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果所參照的 section 不屬於目前的簡報或未包含任何投影片，則拋出此例外。 |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
建立一個帶有預定義影像的新 Section Zoom 框架，並將其新增至圖形集合的末端。

### 回傳

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 座標（單位：點）。 |
| y | **float** | 新 Section Zoom 框架的 y 座標（單位：點）。 |
| width | **float** | 新 Section Zoom 框架的寬度（單位：點）。 |
| height | **float** | 新 Section Zoom 框架的高度（單位：點）。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)；<br/><br/>必須屬於此簡報且至少包含一張投影片。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 在 Section Zoom 框架中顯示的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果所參照的 section 不屬於目前的簡報或未包含任何投影片，則拋出此例外。 |



### 另請參閱
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)