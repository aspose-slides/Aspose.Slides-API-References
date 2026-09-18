---
title: cubic_bezier_to method
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Pierwszy punkt kierunkowy |
| point2 | **aspose.slides.PointF** | Drugi punkt kierunkowy |
| point3 | **aspose.slides.PointF** | Punkt końcowy |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Pierwszy punkt kierunkowy |
| point2 | **aspose.slides.PointF** | Drugi punkt kierunkowy |
| point3 | **aspose.slides.PointF** | Punkt końcowy |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki


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
Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki


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
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)