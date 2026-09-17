---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
创建指定形状的副本并将其添加到形状集合的末尾。
            克隆的形状保留原始的定位和大小。

### 返回

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape).



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

### 返回

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的形状。 |
| x | **float** | 新形状框架的 x 坐标，单位为点。 |
| y | **float** | 新形状框架的 y 坐标，单位为点。 |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
创建指定形状的副本并将其添加到形状集合的末尾。

### 返回

新创建的[`IShape`](/slides/python-net/zh/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要克隆的形状。 |
| x | **float** | 新形状框架的 x 坐标，单位为点。 |
| y | **float** | 新形状框架的 y 坐标，单位为点。 |
| width | **float** | 新形状框架的宽度，单位为点。 |
| height | **float** | 新形状框架的高度，单位为点。 |



### 另见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)