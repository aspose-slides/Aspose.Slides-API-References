---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
创建一个新的连接器形状并将其插入形状集合的指定索引位置，应用默认模板样式。

### Returns
新创建的 [`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 要插入连接器形状的基于零的索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的连接器形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |

## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
创建一个新的连接器形状并将其插入形状集合的指定索引位置，可选择是否应用默认模板样式。

### Returns
新创建的 [`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 要插入连接器形状的基于零的索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的连接器形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标，单位为点。 |
| y | **float** | 连接器框架的 y 坐标，单位为点。 |
| width | **float** | 连接器框架的宽度，单位为点。 |
| height | **float** | 连接器框架的高度，单位为点。 |
| create_from_template | **bool** | 为 true 时应用默认模板样式（非空名称，简易样式）；<br/><br/> 为 false 时使用默认属性值创建连接器。 |

### See Also
* class [`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)
* class [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)