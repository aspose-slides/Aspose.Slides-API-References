---
title: line_to method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
Přidá čáru na konec cesty


```python
def line_to(self, point):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Koncový bod čáry |


## line_to(self, x, y) {#float-float}
Přidá čáru na konec cesty


```python
def line_to(self, x, y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X souřadnice koncového bodu čáry |
| y | **float** | Y souřadnice koncového bodu čáry |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Přidá čáru na určené místo cesty


```python
def line_to(self, point, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Koncový bod |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## line_to(self, x, y, index) {#float-float-int}
Přidá čáru na určené místo cesty


```python
def line_to(self, x, y, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X souřadnice bodu |
| y | **float** | Y souřadnice bodu |
| index | **int** | Index segmentu v PathData |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)