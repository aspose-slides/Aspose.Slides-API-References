---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
建立具有預設範本樣式的新連接器形狀，並將其加入形狀集合的末端。

### 回傳值

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增的連接器形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接器框架的 x 座標，以點為單位。 |
| y | **float** | 連接器框架的 y 座標，以點為單位。 |
| width | **float** | 連接器框架的寬度，以點為單位。 |
| height | **float** | 連接器框架的高度，以點為單位。 |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
建立新連接器形狀並將其加入形狀集合的末端，可選地套用預設範本樣式。

### 回傳值

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要建立的連接器形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接器框架的 x 座標，以點為單位。 |
| y | **float** | 連接器框架的 y 座標，以點為單位。 |
| width | **float** | 連接器框架的寬度，以點為單位。 |
| height | **float** | 連接器框架的高度，以點為單位。 |
| create_from_template | **bool** | True 以套用預設範本樣式（非空名稱，簡單樣式）；<br/><br/>false 以使用預設屬性值建立連接器。 |

### 參見
* 類別 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)