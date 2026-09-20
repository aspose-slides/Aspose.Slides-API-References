---
title: quadratic_bezier_to method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Přidá kvadratickou Bezierovu křivku na konci cesty


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Směrový bod |
| point2 | **aspose.slides.PointF** | Koncový bod |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Přidá kvadratickou Bezierovu křivku do určeného místa cesty


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Směrový bod |
| point2 | **aspose.slides.PointF** | Koncový bod |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Přidá kvadratickou Bezierovu křivku na konci cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice směrového bodu |
| y1 | **float** | Y souřadnice směrového bodu |
| x2 | **float** | X souřadnice koncového bodu |
| y2 | **float** | Y souřadnice koncového bodu |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Přidá kvadratickou Bezierovu křivku do určeného místa cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice směrového bodu |
| y1 | **float** | Y souřadnice směrového bodu |
| x2 | **float** | X souřadnice koncového bodu |
| y2 | **float** | Y souřadnice koncového bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`GeometryPath`](/slides/python-net/cs/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)