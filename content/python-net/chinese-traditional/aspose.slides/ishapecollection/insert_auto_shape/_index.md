---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
建立一個新的自動圖形，並將其插入至圖形集合中的指定索引位置，套用預設範本格式。

### 返回

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 在以零為基礎的索引處插入新自動圖形的位置。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 圖形框架的 x 座標，單位為點。 |
| y | **float** | 圖形框架的 y 座標，單位為點。 |
| width | **float** | 圖形框架的寬度，單位為點。 |
| height | **float** | 圖形框架的高度，單位為點。 |

## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
建立一個新的自動圖形，並將其插入至圖形集合中的指定索引位置，亦可選擇以預設範本樣式初始化。

### 返回

新建立的 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)。

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 在以零為基礎的索引處插入自動圖形的位置。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的自動圖形的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 圖形框架的 x 座標，單位為點。 |
| y | **float** | 圖形框架的 y 座標，單位為點。 |
| width | **float** | 圖形框架的寬度，單位為點。 |
| height | **float** | 圖形框架的高度，單位為點。 |
| create_from_template | **bool** | True 以套用預設範本樣式（包含非空名稱、簡單樣式與置中文字）；<br/><br/>false 以使用所有屬性預設值建立圖形。 |

### 另見
* 類別 [`IAutoShape`](/slides/python-net/zh-hant/aspose.slides/iautoshape)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)