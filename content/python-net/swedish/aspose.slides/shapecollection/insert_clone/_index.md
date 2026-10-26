---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
Den klonade formen behåller den ursprungliga positionen och storleken.

### Returnerar

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Det [`IShape`](/slides/python-net/sv/aspose.slides/ishape) som ska klonas. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
Den nya formen behåller bredden och höjden på `source_shape`.

### Returnerar

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Det [`IShape`](/slides/python-net/sv/aspose.slides/ishape) som ska klonas. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Det nysskapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Det [`IShape`](/slides/python-net/sv/aspose.slides/ishape) som ska klonas. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |
| width | **float** | Bredden på den klonade formens ram, i punkter. |
| height | **float** | Höjden på den klonade formens ram, i punkter. |



### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)