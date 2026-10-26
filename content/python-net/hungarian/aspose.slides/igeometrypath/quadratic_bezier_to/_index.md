---
title: quadratic_bezier_to method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Quadratikus Bézier-görbét ad az út végéhez


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Quadratikus Bézier-görbét ad a megadott helyen az úton


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül van a PathData tartományán |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Quadratikus Bézier-görbét ad az út végéhez


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | X koordináta az iránypontnál |
| y1 | **float** | Y koordináta az iránypontnál |
| x2 | **float** | X koordináta a végpontnál |
| y2 | **float** | Y koordináta a végpontnál |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Quadratikus Bézier-görbét ad a megadott helyen az úton


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | X koordináta az iránypontnál |
| y1 | **float** | Y koordináta az iránypontnál |
| x2 | **float** | X koordináta a végpontnál |
| y2 | **float** | Y koordináta a végpontnál |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül van a PathData tartományán |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)