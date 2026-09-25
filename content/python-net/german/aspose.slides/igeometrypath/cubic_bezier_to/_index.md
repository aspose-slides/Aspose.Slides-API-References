---
title: cubic_bezier_to method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Erster Richtungspunkt |
| point2 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Zweiter Richtungspunkt |
| point3 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Erster Richtungspunkt |
| point2 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Zweiter Richtungspunkt |
| point3 | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Endpunkt |
| index | **int** | Index des Segments in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment-Index liegt außerhalb des PathData-Bereichs |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X-Koordinate des ersten Richtungspunkts |
| y1 | **float** | Y-Koordinate des ersten Richtungspunkts |
| x2 | **float** | X-Koordinate des zweiten Richtungspunkts |
| y2 | **float** | Y-Koordinate des zweiten Richtungspunkts |
| x3 | **float** | X-Koordinate des Endpunkts |
| y3 | **float** | Y-Koordinate des Endpunkts |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x1 | **float** | X-Koordinate des ersten Richtungspunkts |
| y1 | **float** | Y-Koordinate des ersten Richtungspunkts |
| x2 | **float** | X-Koordinate des zweiten Richtungspunkts |
| y2 | **float** | Y-Koordinate des zweiten Richtungspunkts |
| x3 | **float** | X-Koordinate des Endpunkts |
| y3 | **float** | Y-Koordinate des Endpunkts |
| index | **int** | Index des Segments in PathData |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment-Index liegt außerhalb des PathData-Bereichs |



### Siehe auch
* Klasse [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)
* Klasse [`PointF`](/slides/python-net/de/aspose.slides/pointf)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)