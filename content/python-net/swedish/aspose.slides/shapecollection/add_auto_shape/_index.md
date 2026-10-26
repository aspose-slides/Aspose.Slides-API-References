---
title: add_auto_shape method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Skapar en ny automatisk form med standardformatering och lägger till den i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den automatiska formen som ska läggas till. |
| x | **float** | x-koordinaten för formens ram, i punkter. |
| y | **float** | y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Skapar en ny automatisk form och lägger till den i slutet av formsamlingen, eventuellt med standardmallformatering.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Den [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) för den automatiska formen som ska läggas till. |
| x | **float** | x-koordinaten för formens ram, i punkter. |
| y | **float** | y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |
| create_from_template | **bool** | True för att tillämpa standardmallsstil (enkel stil, centrerad text och icke-tomt namn) på den nya formen; false för att skapa formen med alla egenskaper satta till sina standardvärden. |



### Se även
* klass [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)