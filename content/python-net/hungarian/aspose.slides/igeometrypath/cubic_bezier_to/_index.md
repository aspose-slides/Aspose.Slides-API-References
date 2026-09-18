---
title: cubic_bezier_to method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Köbös Bezier-görbét ad a útvonal végéhez


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Első iránypont |
| point2 | **aspose.slides.PointF** | Második iránypont |
| point3 | **aspose.slides.PointF** | Végpont |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Köbös Bezier-görbét ad az útvonal megadott helyéhez


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Első iránypont |
| point2 | **aspose.slides.PointF** | Második iránypont |
| point3 | **aspose.slides.PointF** | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexa kívül esik a PathData tartományán |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Köbös Bezier-görbét ad a útvonal végéhez


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Az első iránypont X koordinátája |
| y1 | **float** | Az első iránypont Y koordinátája |
| x2 | **float** | A második iránypont X koordinátája |
| y2 | **float** | A második iránypont Y koordinátája |
| x3 | **float** | A végpont X koordinátája |
| y3 | **float** | A végpont Y koordinátája |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Köbös Bezier-görbét ad az útvonal megadott helyéhez


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Az első iránypont X koordinátája |
| y1 | **float** | Az első iránypont Y koordinátája |
| x2 | **float** | A második iránypont X koordinátája |
| y2 | **float** | A második iránypont Y koordinátája |
| x3 | **float** | A végpont X koordinátája |
| y3 | **float** | A végpont Y koordinátája |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexa kívül esik a PathData tartományán |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)