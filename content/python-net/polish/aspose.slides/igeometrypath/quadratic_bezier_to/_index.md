---
title: quadratic_bezier_to method
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Dodaje krzywą kwadratową Bézier na końcu ścieżki


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punkt kierunkowy |
| point2 | **aspose.slides.PointF** | Punkt końcowy |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Dodaje krzywą kwadratową Bézier w określonym miejscu ścieżki


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punkt kierunkowy |
| point2 | **aspose.slides.PointF** | Punkt końcowy |
| index | **int** | Indeks segmentu w PathData |


### Wyjątki

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Dodaje krzywą kwadratową Bézier na końcu ścieżki


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | Współrzędna X punktu kierunkowego |
| y1 | **float** | Współrzędna Y punktu kierunkowego |
| x2 | **float** | Współrzędna X punktu końcowego |
| y2 | **float** | Współrzędna Y punktu końcowego |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Dodaje krzywą kwadratową Bézier w określonym miejscu ścieżki


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | Współrzędna X punktu kierunkowego |
| y1 | **float** | Współrzędna Y punktu kierunkowego |
| x2 | **float** | Współrzędna X punktu końcowego |
| y2 | **float** | Współrzędna Y punktu końcowego |
| index | **int** | Indeks segmentu w PathData |


### Wyjątki

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |



### Zobacz także
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)