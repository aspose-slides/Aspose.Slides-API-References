---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
建立一個新的連接器形狀，並將其插入到指定索引的形狀集合中，套用預設範本樣式。

### 傳回值

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入連接器形狀的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的連接器形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接器框架的 x 座標（以點為單位）。 |
| y | **float** | 連接器框架的 y 座標（以點為單位）。 |
| width | **float** | 連接器框架的寬度（以點為單位）。 |
| height | **float** | 連接器框架的高度（以點為單位）。 |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
建立一個新的連接器形狀，並將其插入到指定索引的形狀集合中，可選擇套用預設範本樣式。

### 傳回值

新建立的 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入連接器形狀的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype) | 要插入的連接器形狀的 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)。 |
| x | **float** | 連接器框架的 x 座標（以點為單位）。 |
| y | **float** | 連接器框架的 y 座標（以點為單位）。 |
| width | **float** | 連接器框架的寬度（以點為單位）。 |
| height | **float** | 連接器框架的高度（以點為單位）。 |
| create_from_template | **bool** | True 為套用預設範本樣式（非空名稱、簡單樣式）；false 為以預設屬性值建立連接器。 |



### 另請參閱
* 類別 [`IConnector`](/slides/python-net/zh-hant/aspose.slides/iconnector)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 列舉 [`ShapeType`](/slides/python-net/zh-hant/aspose.slides/shapetype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)