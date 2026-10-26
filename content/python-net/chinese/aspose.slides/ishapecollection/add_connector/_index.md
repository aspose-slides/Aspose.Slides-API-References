---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
创建一个具有默认模板样式的新连接器形状，并将其添加到形状集合的末尾。

### 返回

新创建的[`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要添加的连接器形状的[`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标（单位：点）。 |
| y | **float** | 连接器框架的 y 坐标（单位：点）。 |
| width | **float** | 连接器框架的宽度（单位：点）。 |
| height | **float** | 连接器框架的高度（单位：点）。 |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
创建一个新连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。

### 返回

新创建的[`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)。

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要创建的连接器形状的[`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 连接器框架的 x 坐标（单位：点）。 |
| y | **float** | 连接器框架的 y 坐标（单位：点）。 |
| width | **float** | 连接器框架的宽度（单位：点）。 |
| height | **float** | 连接器框架的高度（单位：点）。 |
| create_from_template | **bool** | True表示应用默认模板样式（非空名称、简易样式）；<br/><br/>false表示使用默认属性值创建连接器。 |

### 另请参见
* 类 [`IConnector`](/slides/python-net/zh/aspose.slides/iconnector)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 枚举 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)