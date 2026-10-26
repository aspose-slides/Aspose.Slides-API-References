---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
            Den klonade formen behåller originalets position och storlek.

### Returnerar

Det nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
            Den nya formen behåller bredden och höjden på `source_shape`.

### Returnerar

Det nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Formen att klona. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |
| width | **float** | Bredden på den klonade formens ram, i punkter. |
| height | **float** | Höjden på den klonade formens ram, i punkter. |



### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)