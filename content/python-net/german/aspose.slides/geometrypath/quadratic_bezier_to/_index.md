---
title: quadratic_bezier_to method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Fügt am Ende des Pfads eine quadratische Bézierkurve hinzu


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Richtungspunkt |
| point2 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Fügt an der angegebenen Stelle des Pfads eine quadratische Bézierkurve hinzu


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Richtungspunkt |
| point2 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt |
| index | **int** | Index des Segments in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex liegt außerhalb des PathData-Bereichs |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Fügt am Ende des Pfads eine quadratische Bézierkurve hinzu


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X-Koordinate des Richtungspunkts |
| y1 | **float** | Y-Koordinate des Richtungspunkts |
| x2 | **float** | X-Koordinate des Endpunkts |
| y2 | **float** | Y-Koordinate des Endpunkts |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Fügt an der angegebenen Stelle des Pfads eine quadratische Bézierkurve hinzu


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X-Koordinate des Richtungspunkts |
| y1 | **float** | Y-Koordinate des Richtungspunkts |
| x2 | **float** | X-Koordinate des Endpunkts |
| y2 | **float** | Y-Koordinate des Endpunkts |
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