---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
Den kopierade formen behåller originalets position och storlek.

### Returnvärde

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
Den nya formen behåller bredden och höjden av `source_shape`.

### Returnvärde

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Formen att klona. |
| x | **float** | x-koordinaten för den nya formens ram, i punkter. |
| y | **float** | y-koordinaten för den nya formens ram, i punkter. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

### Returnvärde

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Formen att klona. |
| x | **float** | x-koordinaten för den nya formens ram, i punkter. |
| y | **float** | y-koordinaten för den nya formens ram, i punkter. |
| width | **float** | Bredden på den nya formens ram, i punkter. |
| height | **float** | Höjden på den nya formens ram, i punkter. |



### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)