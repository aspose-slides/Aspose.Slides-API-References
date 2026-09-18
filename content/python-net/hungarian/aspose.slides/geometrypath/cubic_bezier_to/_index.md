---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Kúbikus Bezier-görbét ad az útvonal végéhez


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Az első iránypont |
| point2 | **aspose.slides.PointF** | A második iránypont |
| point3 | **aspose.slides.PointF** | A végpont |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Kúbikus Bezier-görbét ad a megadott helyre az útvonalban


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Az első iránypont |
| point2 | **aspose.slides.PointF** | A második iránypont |
| point3 | **aspose.slides.PointF** | A végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe a PathData tartományán kívül van |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Kúbikus Bezier-görbét ad az útvonal végéhez


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
Kúbikus Bezier-görbét ad a megadott helyre az útvonalban


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe a PathData tartományán kívül van |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)