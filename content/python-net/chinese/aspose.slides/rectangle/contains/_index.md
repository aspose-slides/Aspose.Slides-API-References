---
title: contains method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
确定指定的点是否包含在此矩形内。

### 返回值

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/zh/aspose.slides/point) | 要测试的点。接受具有 `x` 和 `y` 属性的任何对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |


## contains(self, rect) {#rectangle}
确定由 `rect` 表示的矩形区域是否完全包含在此矩形内。

### 返回值

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/zh/aspose.slides/rectangle) | 要测试的矩形。接受具有 `x`、`y`、`width` 和 `height` 属性的任何对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |


## contains(self, x, y) {#int-int}
确定指定的点是否包含在此矩形内。

### 返回值

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **int** | 要测试的点的 x 坐标。 |
| y | **int** | 要测试的点的 y 坐标。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **TypeError** | 参数数量错误。 |



### 另请参阅
* 类 [`Point`](/slides/python-net/zh/aspose.slides/point)
* 类 [`Rectangle`](/slides/python-net/zh/aspose.slides/rectangle)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)