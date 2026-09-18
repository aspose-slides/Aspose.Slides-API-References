---
title: quadratic_bezier_to method
second_title: Aspose.Slides a Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Kvadratikus Bézier-görbét ad az út végéhez


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Irány pont |
| point2 | **aspose.slides.PointF** | Végpont |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Kvadratikus Bézier-görbét ad az út megadott helyéhez


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Irány pont |
| point2 | **aspose.slides.PointF** | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Kvadratikus Bézier-görbét ad az út végéhez


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | X koordináta az irány pontnál |
| y1 | **float** | Y koordináta az irány pontnál |
| x2 | **float** | X koordináta a végponton |
| y2 | **float** | Y koordináta a végponton |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Kvadratikus Bézier-görbét ad az út megadott helyéhez


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | X koordináta az irány pontnál |
| y1 | **float** | Y koordináta az irány pontnál |
| x2 | **float** | X koordináta a végponton |
| y2 | **float** | Y koordináta a végponton |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)