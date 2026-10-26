---
title: line_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Lägger till en linje i slutet av vägen


```python
def line_to(self, point):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt för linjen |


## line_to(self, x, y) {#float-float}
Lägger till en linje i slutet av vägen


```python
def line_to(self, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinat för slutpunkten av linjen |
| y | **float** | Y-koordinat för slutpunkten av linjen |


## line_to(self, point, index) {#asposeslidespointf-int}
Lägger till en linje på angiven plats i vägen


```python
def line_to(self, point, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |


## line_to(self, x, y, index) {#float-float-int}
Lägger till en linje på angiven plats i vägen


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinat för punkten |
| y | **float** | Y-koordinat för punkten |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |



### Se också
* class [`GeometryPath`](/slides/python-net/sv/aspose.slides/geometrypath)
* class [`PointF`](/slides/python-net/sv/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)