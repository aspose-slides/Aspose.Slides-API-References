---
title: cubic_bezier_to method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenčního API
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Přidá kubickou Bézierovu křivku na konec cesty


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | První řídicí bod |
| point2 | **aspose.slides.PointF** | Druhý řídicí bod |
| point3 | **aspose.slides.PointF** | Koncový bod |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Přidá kubickou Bézierovu křivku na určené místo v cestě


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | První řídicí bod |
| point2 | **aspose.slides.PointF** | Druhý řídicí bod |
| point3 | **aspose.slides.PointF** | Koncový bod |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Přidá kubickou Bézierovu křivku na konec cesty


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice prvního řídicího bodu |
| y1 | **float** | Y souřadnice prvního řídicího bodu |
| x2 | **float** | X souřadnice druhého řídicího bodu |
| y2 | **float** | Y souřadnice druhého řídicího bodu |
| x3 | **float** | X souřadnice koncového bodu |
| y3 | **float** | Y souřadnice koncového bodu |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Přidá kubickou Bézierovu křivku na určené místo v cestě


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x1 | **float** | X souřadnice prvního řídicího bodu |
| y1 | **float** | Y souřadnice prvního řídicího bodu |
| x2 | **float** | X souřadnice druhého řídicího bodu |
| y2 | **float** | Y souřadnice druhého řídicího bodu |
| x3 | **float** | X souřadnice koncového bodu |
| y3 | **float** | Y souřadnice koncového bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)