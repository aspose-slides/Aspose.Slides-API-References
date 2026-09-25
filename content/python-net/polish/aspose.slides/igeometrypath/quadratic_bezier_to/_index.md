---
title: quadratic_bezier_to method
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Dodaje krzywą kwadratową Béziera na końcu ścieżki


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt kierunkowy |
| point2 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Dodaje krzywą kwadratową Béziera w określonym miejscu ścieżki


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt kierunkowy |
| point2 | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Dodaje krzywą kwadratową Béziera na końcu ścieżki


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x1 | **float** | Współrzędna X punktu kierunkowego |
| y1 | **float** | Współrzędna Y punktu kierunkowego |
| x2 | **float** | Współrzędna X punktu końcowego |
| y2 | **float** | Współrzędna Y punktu końcowego |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Dodaje krzywą kwadratową Béziera w określonym miejscu ścieżki


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x1 | **float** | Współrzędna X punktu kierunkowego |
| y1 | **float** | Współrzędna Y punktu kierunkowego |
| x2 | **float** | Współrzędna X punktu końcowego |
| y2 | **float** | Współrzędna Y punktu końcowego |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |



### Zobacz również
* class [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* class [`PointF`](/slides/python-net/pl/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)