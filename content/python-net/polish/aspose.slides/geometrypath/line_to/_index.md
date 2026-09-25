---
title: line_to method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Dodaje odcinek do końca ścieżki


```python
def line_to(self, point):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy odcinka |


## line_to(self, x, y) {#float-float}
Dodaje odcinek do końca ścieżki


```python
def line_to(self, x, y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna X punktu końcowego odcinka |
| y | **float** | Współrzędna Y punktu końcowego odcinka |


## line_to(self, point, index) {#asposeslidespointf-int}
Dodaje odcinek do określonego miejsca ścieżki


```python
def line_to(self, point, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |


## line_to(self, x, y, index) {#float-float-int}
Dodaje odcinek do określonego miejsca ścieżki


```python
def line_to(self, x, y, index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna X punktu |
| y | **float** | Współrzędna Y punktu |
| index | **int** | Indeks segmentu w PathData |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Indeks segmentu jest poza zakresem PathData |



### See Also
* klasa [`GeometryPath`](/slides/python-net/pl/aspose.slides/geometrypath)
* klasa [`PointF`](/slides/python-net/pl/aspose.slides/pointf)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)