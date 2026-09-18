---
title: quadratic_bezier_to method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Quadratikus Bézier-görbét ad hozzá az út végéhez


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Irányító pont |
| point2 | **aspose.slides.PointF** | Végpont |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Quadratikus Bézier-görbét ad a megadott helyhez az úton


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Irányító pont |
| point2 | **aspose.slides.PointF** | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens index kívül esik a PathData tartományon |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Quadratikus Bézier-görbét ad hozzá az út végéhez


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Irányító pont X koordinátája |
| y1 | **float** | Irányító pont Y koordinátája |
| x2 | **float** | Végpont X koordinátája |
| y2 | **float** | Végpont Y koordinátája |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Quadratikus Bézier-görbét ad a megadott helyhez az úton


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Irányító pont X koordinátája |
| y1 | **float** | Irányító pont Y koordinátája |
| x2 | **float** | Végpont X koordinátája |
| y2 | **float** | Végpont Y koordinátája |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens index kívül esik a PathData tartományon |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)