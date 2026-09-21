---
title: add_connector method
second_title: Aspose.Slides 用於 Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
建立具有預設範本樣式的新連接線形狀，並將其加入形狀集合的末端。

### Returns

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要新增的連接線形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接線框架的 X 座標（單位：點）。 |
| y | **float** | 連接線框架的 Y 座標（單位：點）。 |
| width | **float** | 連接線框架的寬度（單位：點）。 |
| height | **float** | 連接線框架的高度（單位：點）。 |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
建立新連接線形狀並將其加入形狀集合的末端，可選地套用預設範本樣式。

### Returns

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要建立的連接線形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接線框架的 X 座標（單位：點）。 |
| y | **float** | 連接線框架的 Y 座標（單位：點）。 |
| width | **float** | 連接線框架的寬度（單位：點）。 |
| height | **float** | 連接線框架的高度（單位：點）。 |
| create_from_template | **bool** | True 代表套用預設範本樣式（非空名稱、簡單樣式）；<br/><br/>false 代表以預設屬性值建立連接線。 |



### See Also
* 類別 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)