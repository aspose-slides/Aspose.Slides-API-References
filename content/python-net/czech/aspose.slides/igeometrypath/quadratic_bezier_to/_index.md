---
title: quadratic_bezier_to method
second_title: Aspose.Slides pro Python přes .NET - referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Přidá kvadratickou Bezierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Bod směru |
| point2 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Přidá kvadratickou Bezierovu křivku na zadané místo v cestě


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Bod směru |
| point2 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Přidá kvadratickou Bezierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | Souřadnice X bodu směru |
| y1 | **float** | Souřadnice Y bodu směru |
| x2 | **float** | Souřadnice X koncového bodu |
| y2 | **float** | Souřadnice Y koncového bodu |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Přidá kvadratickou Bezierovu křivku na zadané místo v cestě


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | Souřadnice X bodu směru |
| y1 | **float** | Souřadnice Y bodu směru |
| x2 | **float** | Souřadnice X koncového bodu |
| y2 | **float** | Souřadnice Y koncového bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* třída [`PointF`](/slides/python-net/cs/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)