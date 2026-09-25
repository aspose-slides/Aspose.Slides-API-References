---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
在路径末尾添加二次贝塞尔曲线

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 方向点 |
| point2 | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 终点 |

## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
在路径的指定位置添加二次贝塞尔曲线

```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 方向点 |
| point2 | [`PointF`](/slides/python-net/zh/aspose.slides/pointf) | 终点 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
在路径末尾添加二次贝塞尔曲线

```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 终点的 X 坐标 |
| y2 | **float** | 终点的 Y 坐标 |

## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
在路径的指定位置添加二次贝塞尔曲线

```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 终点的 X 坐标 |
| y2 | **float** | 终点的 Y 坐标 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |

### 参见
* 类 [`GeometryPath`](/slides/python-net/zh/aspose.slides/geometrypath)
* 类 [`PointF`](/slides/python-net/zh/aspose.slides/pointf)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)