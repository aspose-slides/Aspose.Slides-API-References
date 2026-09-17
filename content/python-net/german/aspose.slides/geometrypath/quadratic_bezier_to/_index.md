---
title: quadratic_bezier_to method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex liegt außerhalb des PathData-Bereichs |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex liegt außerhalb des PathData-Bereichs |



### Siehe auch
* Klasse [`GeometryPath`](/slides/python-net/de/aspose.slides/geometrypath)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)