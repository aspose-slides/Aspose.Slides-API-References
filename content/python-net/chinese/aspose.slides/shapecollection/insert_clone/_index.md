---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
创建指定形状的副本，并将其插入到形状集合中指定的索引位置。  
克隆的形状保留原始位置和大小。

### 返回

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 零基索引，用于插入克隆形状的位置。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
创建指定形状的副本，并将其插入到形状集合中指定的索引位置。  
新形状保留 `source_shape` 的宽度和高度。

### 返回

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 零基索引，用于插入克隆形状的位置。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
创建指定形状的副本，并将其插入到形状集合中指定的索引位置。

### 返回

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 零基索引，用于插入克隆形状的位置。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |
| width | **float** | 克隆形状框架的宽度，单位为点。 |
| height | **float** | 克隆形状框架的高度，单位为点。 |

### 参见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)