---
title: line_to method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometrypath/line_to/
weight: 40
---


## line_to {#asposepydrawingpointf}
Adds line to the end of the path


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.pydrawing.PointF** | End point of the line |


## line_to {#float-float}
Adds line to the end of the path


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of the end point of the line |
| y | **float** | Y coordinate of the end point of the line |


## line_to {#asposepydrawingpointf-int}
Adds line to the specified place of the path


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.pydrawing.PointF** | End point |
| index | **int** | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## line_to {#float-float-int}
Adds line to the specified place of the path


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of the point |
| y | **float** | Y coordinate of the point |
| index | **int** | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### See Also
* class [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

