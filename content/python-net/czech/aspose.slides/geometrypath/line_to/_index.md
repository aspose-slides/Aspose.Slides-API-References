---
title: line_to method
second_title: Aspose.Slides pro Python prostřednictvím .NET API referenční příručky
description: 
type: docs
url: /cs/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Přidá čáru na konec cesty


```python
def line_to(self, point):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod čáry |


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


## line_to(self, point, index) {#asposeslidespointf-int}
Přidá čáru na určené místo cesty


```python
def line_to(self, point, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Koncový bod |
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
* třída [`GeometryPath`](/slides/python-net/cs/aspose.slides/geometrypath)
* třída [`PointF`](/slides/python-net/cs/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)