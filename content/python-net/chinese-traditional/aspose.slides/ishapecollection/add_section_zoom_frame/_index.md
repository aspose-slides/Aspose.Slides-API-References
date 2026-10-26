---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
建立一個新的 Section Zoom 框架，並將其新增至形狀集合的末端。

### 返回

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)； <br/><br/> 必須屬於此簡報且至少包含一張投影片。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的節不屬於目前的簡報或不包含任何投影片，則拋出此例外。 |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
建立一個具備預設圖像的新的 Section Zoom 框架，並將其新增至形狀集合的末端。

### 返回

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | **float** | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | **float** | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | **float** | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)； <br/><br/> 必須屬於此簡報且至少包含一張投影片。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 用於在 Section Zoom 框架中顯示的 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果參照的節不屬於目前的簡報或不包含任何投影片，則拋出此例外。 |

### 另請參閱
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)