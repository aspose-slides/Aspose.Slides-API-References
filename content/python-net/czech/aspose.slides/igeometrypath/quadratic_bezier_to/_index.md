---
title: quadratic_bezier_to method
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Přidá kvadratickou Bézierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Směrový bod |
| point2 | **aspose.slides.PointF** | Koncový bod |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Přidá kvadratickou Bézierovu křivku do určeného místa v cestě


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
Přidá kvadratickou Bézierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X-souřadnice řídícího bodu |
| y1 | **float** | Y-souřadnice řídícího bodu |
| x2 | **float** | X-souřadnice koncového bodu |
| y2 | **float** | Y-souřadnice koncového bodu |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Přidá kvadratickou Bézierovu křivku do určeného místa v cestě


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X-souřadnice řídícího bodu |
| y1 | **float** | Y-souřadnice řídícího bodu |
| x2 | **float** | X-souřadnice koncového bodu |
| y2 | **float** | Y-souřadnice koncového bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)