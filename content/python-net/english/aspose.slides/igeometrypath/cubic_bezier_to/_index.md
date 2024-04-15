---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---


## cubic_bezier_to {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Adds cubic Bezier curve at the end the path


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | aspose.pydrawing.PointF | First direction point |
| point2 | aspose.pydrawing.PointF | Second direction point |
| point3 | aspose.pydrawing.PointF | End point |



## cubic_bezier_to {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Adds cubic Bezier curve to the specified place of the path


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | aspose.pydrawing.PointF | First direction point |
| point2 | aspose.pydrawing.PointF | Second direction point |
| point3 | aspose.pydrawing.PointF | End point |
| index | int | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentOutOfRangeException** | Segment index is out of PathData range |



## cubic_bezier_to {#float-float-float-float-float-float}
Adds cubic Bezier curve at the end the path


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |



## cubic_bezier_to {#float-float-float-float-float-float-int}
Adds cubic Bezier curve to the specified place of the path


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |
| index | int | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentOutOfRangeException** | Segment index is out of PathData range |



### See Also
* class [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
