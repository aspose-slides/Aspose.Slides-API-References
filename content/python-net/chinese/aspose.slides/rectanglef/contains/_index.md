---
title: contains method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
确定指定的点是否位于此矩形内。

### 返回

`True` 如果点位于此矩形内则返回 `True`；否则返回 `False`.



```python
def contains(self, point):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 要测试的点。接受任何具有 `x` 和 `y` 属性的对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |


## contains(self, rect) {#rectanglef}
确定由 `rect` 表示的矩形区域是否完全位于此矩形内。

### 返回

`True` 如果由 `rect` 表示的矩形区域完全位于此矩形内则返回 `True`；否则返回 `False`.



```python
def contains(self, rect):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef) | 要测试的矩形。接受任何具有 `x`、`y`、`width` 和 `height` 属性的对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |


## contains(self, x, y) {#float-float}
确定指定的点是否位于此矩形内。

### 返回

`True` 如果由 `x` 和 `y` 定义的点位于此矩形内则返回 `True`；否则返回 `False`.



```python
def contains(self, x, y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 要测试的点的 x 坐标。 |
| y | **float** | 要测试的点的 y 坐标。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |



### 另请参见
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 类 [`RectangleF`](/slides/python-net/zh/aspose.slides/rectanglef)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)