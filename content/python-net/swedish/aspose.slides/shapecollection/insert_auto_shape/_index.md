---
title: insert_auto_shape method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet,
            med standardmallformatering.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den nya automatiska formen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den automatiska formen som ska infogas. |
| x | **float** | Formens ram x-koordinat, i punkter. |
| y | **float** | Formens ram y-koordinat, i punkter. |
| width | **float** | Formens rambredd, i punkter. |
| height | **float** | Formens ramhöjd, i punkter. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet,
            alternativt initierar den med standardmallstil.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den automatiska formen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den automatiska formen som ska infogas. |
| x | **float** | Formens ram x-koordinat, i punkter. |
| y | **float** | Formens ram y-koordinat, i punkter. |
| width | **float** | Formens rambredd, i punkter. |
| height | **float** | Formens ramhöjd, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallstil (inklusive ett icke-tomt namn, enkel stil och centrerad text); <br/><br/>            false för att skapa formen med alla egenskaper satta till sina standardvärden. |



### Se även
* klass [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)