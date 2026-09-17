---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
创建一个新的连接器形状，并将其插入到形状集合中指定的索引位置，应用默认的模板样式。

### 返回

新创建的[`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入连接器形状的基于零的索引位置。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的连接器形状的[`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |

## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
创建一个新的连接器形状，并将其插入到形状集合中指定的索引位置，可选择性地应用默认的模板样式。

### 返回

新创建的[`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 插入连接器形状的基于零的索引位置。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的连接器形状的[`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |
| create_from_template | **bool** | True 表示应用默认模板样式（非空名称，简易样式）；<br/><br/>false 表示使用默认属性值创建连接器。 |

### 另见
* 类 [`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 枚举 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)