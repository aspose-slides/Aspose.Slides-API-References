---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
建立一個新的自動圖形，並將其插入到指定索引位置的圖形集合中，套用預設的範本格式。

### 返回

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入新自動圖形的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 圖形框架的 x 坐標（單位為點）。 |
| y | **float** | 圖形框架的 y 坐標（單位為點）。 |
| width | **float** | 圖形框架的寬度（單位為點）。 |
| height | **float** | 圖形框架的高度（單位為點）。 |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
建立一個新的自動圖形，並將其插入到指定索引位置的圖形集合中，亦可選擇性地以預設範本樣式進行初始化。

### 返回

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入自動圖形的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 圖形框架的 x 坐標（單位為點）。 |
| y | **float** | 圖形框架的 y 坐標（單位為點）。 |
| width | **float** | 圖形框架的寬度（單位為點）。 |
| height | **float** | 圖形框架的高度（單位為點）。 |
| create_from_template | **bool** | True 若套用預設範本樣式（包括非空名稱、簡易樣式和置中文字）；<br/><br/>false 若建立圖形時所有屬性皆設為預設值。 |



### 另請參閱
* 類別 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)