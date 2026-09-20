---
title: line_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
Lägger till en linje i slutet av sökvägen


```python
def line_to(self, point):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Slutpunkt för linjen |


## line_to(self, x, y) {#float-float}
Lägger till en linje i slutet av sökvägen


```python
def line_to(self, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinat för linjens slutpunkt |
| y | **float** | Y-koordinat för linjens slutpunkt |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Lägger till en linje på den angivna platsen i sökvägen


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför området för PathData |


## line_to(self, x, y, index) {#float-float-int}
Lägger till en linje på den angivna platsen i sökvägen


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför området för PathData |



### Se också
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)