---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---


## quadratic_bezier_to {#asposepydrawingpointf-asposepydrawingpointf}
Adds quadratic Bezier curve at the end the path


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | aspose.pydrawing.PointF | Direction point |
| point2 | aspose.pydrawing.PointF | End point |



## quadratic_bezier_to {#asposepydrawingpointf-asposepydrawingpointf-int}
Adds quadratic Bezier curve to the specified place of the path


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | aspose.pydrawing.PointF | Direction point |
| point2 | aspose.pydrawing.PointF | End point |
| index | int | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentOutOfRangeException | Segment index is out of PathData range |



## quadratic_bezier_to {#float-float-float-float}
Adds quadratic Bezier curve at the end the path


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |



## quadratic_bezier_to {#float-float-float-float-int}
Adds quadratic Bezier curve to the specified place of the path


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |
| index | int | Index of segment in PathData |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentOutOfRangeException | Segment index is out of PathData range |



