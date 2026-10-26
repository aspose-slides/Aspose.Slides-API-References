---
title: insert_auto_shape method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
创建一个新的自动形状并将其插入到指定索引的形状集合中，应用默认模板格式。

### 返回值

新创建的 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入新自动形状的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的自动形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 形状框架的 x 坐标，单位为点。 |
| y | **float** | 形状框架的 y 坐标，单位为点。 |
| width | **float** | 形状框架的宽度，单位为点。 |
| height | **float** | 形状框架的高度，单位为点。 |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
创建一个新的自动形状并将其插入到指定索引的形状集合中，可选择使用默认模板样式进行初始化。

### 返回值

新创建的 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入自动形状的零基索引。 |
| shape_type | [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype) | 要插入的自动形状的 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)。 |
| x | **float** | 形状框架的 x 坐标，单位为点。 |
| y | **float** | 形状框架的 y 坐标，单位为点。 |
| width | **float** | 形状框架的宽度，单位为点。 |
| height | **float** | 形状框架的高度，单位为点。 |
| create_from_template | **bool** | True 表示应用默认模板样式（包括非空名称、简易样式和居中文本）；<br/><br/>false 表示创建形状时所有属性均使用默认值。 |



### 另请参见
* 类 [`IAutoShape`](/slides/python-net/zh/aspose.slides/iautoshape)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 枚举 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)