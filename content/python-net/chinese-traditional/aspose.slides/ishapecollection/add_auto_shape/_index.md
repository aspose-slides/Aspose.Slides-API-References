---
title: add_auto_shape method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
建立一個具有預設格式的自動圖形，並將其新增至形狀集合的末端。

### Returns

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增之自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 形狀框架的 x 座標（單位：點）。 |
| y | **float** | 形狀框架的 y 座標（單位：點）。 |
| width | **float** | 形狀框架的寬度（單位：點）。 |
| height | **float** | 形狀框架的高度（單位：點）。 |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
建立一個新的自動圖形，將其新增至形狀集合的末端，並可選擇以預設範本格式初始化。

### Returns

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增之自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 形狀框架的 x 座標（單位：點）。 |
| y | **float** | 形狀框架的 y 座標（單位：點）。 |
| width | **float** | 形狀框架的寬度（單位：點）。 |
| height | **float** | 形狀框架的高度（單位：點）。 |
| create_from_template | **bool** | True 代表套用預設範本樣式（簡易樣式、文字置中且名稱非空白）<br/><br/>            至新圖形；false 代表建立圖形時所有屬性皆使用預設值。 |

### 參見
* class [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)
* class [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)