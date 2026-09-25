---
title: cubic_bezier_to method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Hozzáad egy köbös Bézier-görbét az útvonal végéhez


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Első iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Második iránypont |
| point3 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Hozzáad egy köbös Bézier-görbét a megadott helyre az útvonalon


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Első iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Második iránypont |
| point3 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Hozzáad egy köbös Bézier-görbét az útvonal végéhez


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
Hozzáad egy köbös Bézier-görbét a megadott helyre az útvonalon


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)