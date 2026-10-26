---
title: line_to method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Dodaje linię do końca ścieżki


```python
def line_to(self, point):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt końcowy linii |


## line_to(self, x, y) {#float-float}
Dodaje linię do końca ścieżki


```python
def line_to(self, x, y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna X punktu końcowego linii |
| y | **float** | Współrzędna Y punktu końcowego linii |


## line_to(self, point, index) {#asposeslidespointf-int}
Dodaje linię do określonego miejsca ścieżki


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
Dodaje linię do określonego miejsca ścieżki


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



### Zobacz także
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* klasa [`PointF`](/slides/python-net/pl/aspose.slides/pointf)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)