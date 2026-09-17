---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
创建指定形状的副本并将其插入形状集合的指定索引位置。克隆的形状保留原始的位置信息和大小。

### 返回值

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入克隆形状的从零开始的索引。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
创建指定形状的副本并将其插入形状集合的指定索引位置。新形状保留 `source_shape` 的宽度和高度。

### 返回值

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入克隆形状的从零开始的索引。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| x | **float** | 克隆形状框的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框的 y 坐标，单位为点。 |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
创建指定形状的副本并将其插入形状集合的指定索引位置。

### 返回值

新创建的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入克隆形状的从零开始的索引。 |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| x | **float** | 克隆形状框的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框的 y 坐标，单位为点。 |
| width | **float** | 克隆形状框的宽度，单位为点。 |
| height | **float** | 克隆形状框的高度，单位为点。 |

### 参见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)