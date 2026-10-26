---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
创建一个具有默认格式的新自动形状，并将其添加到形状集合的末尾。

### 返回

新创建的 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要添加的自动形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 形状框架的 x 坐标（单位：磅）。 |
| y | **float** | 形状框架的 y 坐标（单位：磅）。 |
| width | **float** | 形状框架的宽度（单位：磅）。 |
| height | **float** | 形状框架的高度（单位：磅）。 |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。

### 返回

新创建的 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape)。

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要添加的自动形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 形状框架的 x 坐标（单位：磅）。 |
| y | **float** | 形状框架的 y 坐标（单位：磅）。 |
| width | **float** | 形状框架的宽度（单位：磅）。 |
| height | **float** | 形状框架的高度（单位：磅）。 |
| create_from_template | **bool** | True 表示对新形状应用默认模板样式（简易样式、居中文本和非空名称）<br/><br/>            false 表示创建形状时所有属性均设置为默认值。 |

### 另请参阅
* 类 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 枚举 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)