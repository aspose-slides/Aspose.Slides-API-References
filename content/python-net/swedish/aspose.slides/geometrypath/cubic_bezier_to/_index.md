---
title: cubic_bezier_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Lägger till en kubisk Bezier-kurva i slutet av vägen


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Lägger till en kubisk Bezier-kurva på den angivna platsen i vägen


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Lägger till en kubisk Bezier-kurva i slutet av vägen


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Lägger till en kubisk Bezier-kurva på den angivna platsen i vägen


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### Se även
* klass [`GeometryPath`](/slides/python-net/sv/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)