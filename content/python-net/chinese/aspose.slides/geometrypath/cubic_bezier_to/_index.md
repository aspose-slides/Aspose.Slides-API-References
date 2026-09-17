---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
在路径末尾添加三次贝塞尔曲线


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 第一个方向点 |
| point2 | **aspose.slides.PointF** | 第二个方向点 |
| point3 | **aspose.slides.PointF** | 结束点 |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
在路径的指定位置添加三次贝塞尔曲线


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 第一个方向点 |
| point2 | **aspose.slides.PointF** | 第二个方向点 |
| point3 | **aspose.slides.PointF** | 结束点 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
在路径末尾添加三次贝塞尔曲线


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x1 | **float** | 第一个方向点的 X 坐标 |
| y1 | **float** | 第一个方向点的 Y 坐标 |
| x2 | **float** | 第二个方向点的 X 坐标 |
| y2 | **float** | 第二个方向点的 Y 坐标 |
| x3 | **float** | 结束点的 X 坐标 |
| y3 | **float** | 结束点的 Y 坐标 |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
在路径的指定位置添加三次贝塞尔曲线


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x1 | **float** | 第一个方向点的 X 坐标 |
| y1 | **float** | 第一个方向点的 Y 坐标 |
| x2 | **float** | 第二个方向点的 X 坐标 |
| y2 | **float** | 第二个方向点的 Y 坐标 |
| x3 | **float** | 结束点的 X 坐标 |
| y3 | **float** | 结束点的 Y 坐标 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |



### 另请参见
* 类 [`GeometryPath`](/slides/python-net/zh/aspose.slides/geometrypath)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)