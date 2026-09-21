---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
在指定的索引處建立一個新的 Section Zoom 框架，並將其插入至圖形集合中。

### 回傳值

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 在此插入 Section Zoom 框架的零基索引。 |
| x | **float** | 新 Section Zoom 框架的 x 座標（以點為單位）。 |
| y | **float** | 新 Section Zoom 框架的 y 座標（以點為單位）。 |
| width | **float** | 新 Section Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 Section Zoom 框架的高度（以點為單位）。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)；<br/><br/>            必須屬於此簡報且至少包含一張投影片。 |

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果所參照的節未屬於目前的簡報或不含任何投影片，則拋出此例外。 |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
建立一個帶有預先定義圖像的新 Section Zoom 框架，並將其插入至指定索引的圖形集合中。

### 回傳值

新建立的 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)。

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 在此插入 Section Zoom 框架的零基索引。 |
| x | **float** | 新 Section Zoom 框架的 x 座標（以點為單位）。 |
| y | **float** | 新 Section Zoom 框架的 y 座標（以點為單位）。 |
| width | **float** | 新 Section Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 Section Zoom 框架的高度（以點為單位）。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 此 Section Zoom 框架所參照的 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)；<br/><br/>            必須屬於此簡報且至少包含一張投影片。 |
| image | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 在 Section Zoom 框架內顯示的圖像。 |

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 如果所參照的節未屬於目前的簡報或不含任何投影片，則拋出此例外。 |

### 另請參閱
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/isectionzoomframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)