---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
创建指定形状的副本并将其添加到形状集合的末尾。
            克隆的形状保留原始形状的位置和大小。

### 返回值

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def add_clone(self, source_shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

## add_clone(self, source_shape, x, y) {#ishape-float-float}
创建指定形状的副本并将其添加到形状集合的末尾。
            新形状保留 `source_shape` 的宽度和高度。

### 返回值

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def add_clone(self, source_shape, x, y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |

## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
创建指定形状的副本并将其添加到形状集合的末尾。

### 返回值

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的形状。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |
| width | **float** | 克隆形状框架的宽度，单位为点。 |
| height | **float** | 克隆形状框架的高度，单位为点。 |

### 另见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)