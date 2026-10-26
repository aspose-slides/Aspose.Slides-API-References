---
title: cubic_bezier_to method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Dodaje krzywą Bézier trzeciego stopnia na końcu ścieżki


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Pierwszy punkt kierunkowy |
| point2 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Drugi punkt kierunkowy |
| point3 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Dodaje krzywą Bézier trzeciego stopnia w określonym miejscu ścieżki


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Pierwszy punkt kierunkowy |
| point2 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Drugi punkt kierunkowy |
| point3 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Dodaje krzywą Bézier trzeciego stopnia na końcu ścieżki


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x1 | **float** | Współrzędna X pierwszego punktu kierunkowego |
| y1 | **float** | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | **float** | Współrzędna X drugiego punktu kierunkowego |
| y2 | **float** | Współrzędna Y drugiego punktu kierunkowego |
| x3 | **float** | Współrzędna X punktu końcowego |
| y3 | **float** | Współrzędna Y punktu końcowego |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Dodaje krzywą Bézier trzeciego stopnia w określonym miejscu ścieżki


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x1 | **float** | Współrzędna X pierwszego punktu kierunkowego |
| y1 | **float** | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | **float** | Współrzędna X drugiego punktu kierunkowego |
| y2 | **float** | Współrzędna Y drugiego punktu kierunkowego |
| x3 | **float** | Współrzędna X punktu końcowego |
| y3 | **float** | Współrzędna Y punktu końcowego |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |



### Zobacz także
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* klasa [`PointF`](/slides/python-net/pl/aspose.slides/pointf)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)