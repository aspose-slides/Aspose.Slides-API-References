---
title: insert_auto_shape method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Skapar en ny auto form och infogar den i formsamlingen på det angivna indexet, med standardmallformatering.

### Returns

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den nya auto formen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den auto formen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Skapar en ny auto form och infogar den i formsamlingen på det angivna indexet, valfritt med standardmallstyling.

### Returns

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där den auto formen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den auto formen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallstyling (inklusive ett icke-tomt namn, enkel stil och centrerad text); <br/><br/>            false för att skapa formen med alla egenskaper satta till sina standardvärden. |



### Se även
* klass [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)