---
title: line_to method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Fügt eine Linie am Ende des Pfads hinzu


```python
def line_to(self, point):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt der Linie |


## line_to(self, x, y) {#float-float}
Fügt eine Linie am Ende des Pfads hinzu


```python
def line_to(self, x, y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | X-Koordinate des Endpunkts der Linie |
| y | **float** | Y-Koordinate des Endpunkts der Linie |


## line_to(self, point, index) {#asposeslidespointf-int}
Fügt eine Linie an der angegebenen Stelle des Pfads hinzu


```python
def line_to(self, point, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt |
| index | **int** | Index des Segments in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex liegt außerhalb des PathData-Bereichs |


## line_to(self, x, y, index) {#float-float-int}
Fügt eine Linie an der angegebenen Stelle des Pfads hinzu


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | X-Koordinate des Punktes |
| y | **float** | Y-Koordinate des Punktes |
| index | **int** | Index des Segments in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex liegt außerhalb des PathData-Bereichs |



### Siehe auch
* Klasse [`GeometryPath`](/slides/python-net/de/aspose.slides/geometrypath)
* Klasse [`PointF`](/slides/python-net/de/aspose.slides/pointf)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)