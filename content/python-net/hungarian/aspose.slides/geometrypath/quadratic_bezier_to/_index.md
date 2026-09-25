---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
A kvadratikus Bézier-görbét az útvonal végéhez adja


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Irányítási pont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
A kvadratikus Bézier-görbét a megadott helyre az útvonalban adja


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Irányítási pont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |


### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe a PathData tartományán kívül esik |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
A kvadratikus Bézier-görbét az útvonal végéhez adja


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Az irányítási pont X koordinátája |
| y1 | **float** | Az irányítási pont Y koordinátája |
| x2 | **float** | A végpont X koordinátája |
| y2 | **float** | A végpont Y koordinátája |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
A kvadratikus Bézier-görbét a megadott helyre az útvonalban adja


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x1 | **float** | Az irányítási pont X koordinátája |
| y1 | **float** | Az irányítási pont Y koordinátája |
| x2 | **float** | A végpont X koordinátája |
| y2 | **float** | A végpont Y koordinátája |
| index | **int** | A szegmens indexe a PathData-ban |


### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe a PathData tartományán kívül esik |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)