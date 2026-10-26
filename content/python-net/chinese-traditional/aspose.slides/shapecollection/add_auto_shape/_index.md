---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
建立一個具有預設格式的新自動圖形，並將其加入圖形集合的末端。

### 回傳值

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增之自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 形狀框架的 x 座標（單位：點）。 |
| y | **float** | 形狀框架的 y 座標（單位：點）。 |
| width | **float** | 形狀框架的寬度（單位：點）。 |
| height | **float** | 形狀框架的高度（單位：點）。 |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
建立一個新自動圖形，並將其加入圖形集合的末端，可選擇以預設範本格式初始化。

### 回傳值

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增之自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 形狀框架的 x 座標（單位：點）。 |
| y | **float** | 形狀框架的 y 座標（單位：點）。 |
| width | **float** | 形狀框架的寬度（單位：點）。 |
| height | **float** | 形狀框架的高度（單位：點）。 |
| create_from_template | **bool** | True 代表套用預設範本樣式（簡易樣式、置中文字，且名稱非空）<br/><br/>            到新圖形；false 代表建立圖形時所有屬性皆使用預設值。 |

### 另請參閱
* 類別 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)