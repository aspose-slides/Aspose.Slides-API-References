---
title: quadratic_bezier_to method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Přidá kvadratickou Bézierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Bod směru |
| point2 | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Přidá kvadratickou Bézierovu křivku na určené místo cesty


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
Přidá kvadratickou Bézierovu křivku na konec cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice bodu směru |
| y1 | **float** | Y souřadnice bodu směru |
| x2 | **float** | X souřadnice koncového bodu |
| y2 | **float** | Y souřadnice koncového bodu |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Přidá kvadratickou Bézierovu křivku na určené místo cesty


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice bodu směru |
| y1 | **float** | Y souřadnice bodu směru |
| x2 | **float** | X souřadnice koncového bodu |
| y2 | **float** | Y souřadnice koncového bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`GeometryPath`](/slides/python-net/cs/aspose.slides/geometrypath)
* třída [`PointF`](/slides/python-net/cs/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)