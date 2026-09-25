---
title: cubic_bezier_to method
second_title: Aspose.Slides Pythonhoz a .NET API referencián keresztül
description: 
type: docs
url: /hu/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Kubikus Bézier-görbét ad az útvonal végére


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Az első iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | A második iránypont |
| point3 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Kubikus Bézier-görbét ad a megadott helyre az útvonalon


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Az első iránypont |
| point2 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | A második iránypont |
| point3 | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Kubikus Bézier-görbét ad az útvonal végére


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | Az első iránypont X koordinátája |
| y1 | **float** | Az első iránypont Y koordinátája |
| x2 | **float** | A második iránypont X koordinátája |
| y2 | **float** | A második iránypont Y koordinátája |
| x3 | **float** | A végpont X koordinátája |
| y3 | **float** | A végpont Y koordinátája |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Kubikus Bézier-görbét ad a megadott helyre az útvonalon


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | Az első iránypont X koordinátája |
| y1 | **float** | Az első iránypont Y koordinátája |
| x2 | **float** | A második iránypont X koordinátája |
| y2 | **float** | A második iránypont Y koordinátája |
| x3 | **float** | A végpont X koordinátája |
| y3 | **float** | A végpont Y koordinátája |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül esik a PathData tartományán |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)