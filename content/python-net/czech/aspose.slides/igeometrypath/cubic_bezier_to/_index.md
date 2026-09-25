---
title: cubic_bezier_to method
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Přidá kubickou Bezierovu křivku na konec cesty


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | První řídící bod |
| point2 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Druhý řídící bod |
| point3 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Přidá kubickou Bezierovu křivku na určené místo cesty


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | První řídící bod |
| point2 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Druhý řídící bod |
| point3 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Přidá kubickou Bezierovu křivku na konec cesty


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X-souřadnice prvního řídícího bodu |
| y1 | **float** | Y-souřadnice prvního řídícího bodu |
| x2 | **float** | X-souřadnice druhého řídícího bodu |
| y2 | **float** | Y-souřadnice druhého řídícího bodu |
| x3 | **float** | X-souřadnice koncového bodu |
| y3 | **float** | Y-souřadnice koncového bodu |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Přidá kubickou Bezierovu křivku na určené místo cesty


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X-souřadnice prvního řídícího bodu |
| y1 | **float** | Y-souřadnice prvního řídícího bodu |
| x2 | **float** | X-souřadnice druhého řídícího bodu |
| y2 | **float** | Y-souřadnice druhého řídícího bodu |
| x3 | **float** | X-souřadnice koncového bodu |
| y3 | **float** | Y-souřadnice koncového bodu |
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