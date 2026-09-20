---
title: add_auto_shape method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Skapar en ny autoshape med standardformatering och lägger till den i slutet av
            shape-samlingen.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Skapar en ny autoshape och lägger till den i slutet av shape-samlingen, eventuellt
            initierar den med standardmall-formatering.

### Returnerar

Den nyss skapade [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |
| create_from_template | **bool** | True för att tillämpa standardmall-formatering (enkel stil, centrerad text och icke-tomt namn)<br/><br/>            på den nya shape:n; false för att skapa shape:n med alla egenskaper satta till sina standardvärden. |



### Se även
* klass [`IAutoShape`](/slides/python-net/sv/aspose.slides/iautoshape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)