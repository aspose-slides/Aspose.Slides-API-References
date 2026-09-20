---
title: line_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Lägger till en linje i slutet av vägen


```python
def line_to(self, point):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Slutpunkt för linjen |


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


## line_to(self, point, index) {#asposepydrawingpointf-int}
Lägger till en linje på den angivna platsen i vägen


```python
def line_to(self, point, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Slutpunkt |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |


## line_to(self, x, y, index) {#float-float-int}
Lägger till en linje på den angivna platsen i vägen


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



### Se även
* klass [`GeometryPath`](/slides/python-net/sv/aspose.slides/geometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)