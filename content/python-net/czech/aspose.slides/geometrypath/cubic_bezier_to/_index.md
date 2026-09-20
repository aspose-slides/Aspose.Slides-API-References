---
title: cubic_bezier_to method
second_title: Aspose.Slides pro Python přes .NET - reference API
description: 
type: docs
url: /cs/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Přidá kubickou Bézierovu křivku na konec cesty


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Přidá kubickou Bézierovu křivku na určené místo cesty


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | First direction point |
| point2 | **aspose.slides.PointF** | Second direction point |
| point3 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Přidá kubickou Bézierovu křivku na konec cesty


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Přidá kubickou Bézierovu křivku na určené místo cesty


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### Viz také
* třída [`GeometryPath`](/slides/python-net/cs/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)