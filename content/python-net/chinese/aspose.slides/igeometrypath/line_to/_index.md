---
title: line_to method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
在路径的末尾添加直线


```python
def line_to(self, point):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 直线的结束点 |


## line_to(self, x, y) {#float-float}
在路径的末尾添加直线


```python
def line_to(self, x, y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 直线结束点的 X 坐标 |
| y | **float** | 直线结束点的 Y 坐标 |


## line_to(self, point, index) {#asposepydrawingpointf-int}
在路径的指定位置添加直线


```python
def line_to(self, point, index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 结束点 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |


## line_to(self, x, y, index) {#float-float-int}
在路径的指定位置添加直线


```python
def line_to(self, x, y, index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 点的 X 坐标 |
| y | **float** | 点的 Y 坐标 |
| index | **int** | PathData 中段的索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 段索引超出 PathData 范围 |



### 另请参见
* 类 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)