---
title: line_to method
second_title: Aspose.Slides a Python számára a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Vonalat ad a útvonal végéhez


```python
def line_to(self, point):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | A vonal végpontja |


## line_to(self, x, y) {#float-float}
Vonalat ad a útvonal végéhez


```python
def line_to(self, x, y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | A vonal végpontjának X koordinátája |
| y | **float** | A vonal végpontjának Y koordinátája |


## line_to(self, point, index) {#asposeslidespointf-int}
Vonalat ad az útvonal megadott helyéhez


```python
def line_to(self, point, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | Végpont |
| index | **int** | Az útvonal szegmensének indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexa kívül esik a PathData tartományán |


## line_to(self, x, y, index) {#float-float-int}
Vonalat ad az útvonal megadott helyéhez


```python
def line_to(self, x, y, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | A pont X koordinátája |
| y | **float** | A pont Y koordinátája |
| index | **int** | Az útvonal szegmensének indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexa kívül esik a PathData tartományán |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)