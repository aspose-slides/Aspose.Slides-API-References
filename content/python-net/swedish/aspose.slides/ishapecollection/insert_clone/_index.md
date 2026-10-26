---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
            Den klonade formen behåller originalets position och storlek.

### Returnerar

Den nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
            Den nya formen behåller bredden och höjden av `source_shape`.

### Returnerar

Den nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |
| x | **float** | Den x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | Den y-koordinaten för den klonade formens ram, i punkter. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`IShape`](/slides/python-net/sv/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den klonade formen ska infogas. |
| source_shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att klona. |
| x | **float** | Den x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | Den y-koordinaten för den klonade formens ram, i punkter. |
| width | **float** | Bredden på den klonade formens ram, i punkter. |
| height | **float** | Höjden på den klonade formens ram, i punkter. |



### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)