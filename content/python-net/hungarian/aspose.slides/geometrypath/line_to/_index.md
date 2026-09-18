---
title: line_to method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Vonalat ad az útvonal végéhez


```python
def line_to(self, point):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Vonal vége pontja |


## line_to(self, x, y) {#float-float}
Vonalat ad az útvonal végéhez


```python
def line_to(self, x, y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | A vonal végpontjának X koordinátája |
| y | **float** | A vonal végpontjának Y koordinátája |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Vonalat ad az útvonal megadott helyéhez


```python
def line_to(self, point, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül van a PathData tartományán |


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
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens indexe kívül van a PathData tartományán |



### Lásd még
* osztály [`GeometryPath`](/slides/python-net/hu/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)