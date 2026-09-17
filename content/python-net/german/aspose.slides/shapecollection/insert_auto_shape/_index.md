---
title: insert_auto_shape method
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Erstellt eine neue Autoform und fügt sie in die Formsammlung an der angegebenen Position ein, wobei die Standardvorlagenformatierung angewendet wird.

### Rückgabewert

The newly created [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the new auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Erstellt eine neue Autoform und fügt sie in die Formsammlung an der angegebenen Position ein, wobei optional die Standardvorlagenstil angewendet wird.

### Rückgabewert

The newly created [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |
| create_from_template | **bool** | True, um die Standardvorlagenstil anzuwenden (including a non-empty name, simple style, and centered text); <br/><br/> false, um die Form mit allen Eigenschaften auf ihre Standards zu setzen. |



### Siehe auch
* class [`IAutoShape`](/slides/python-net/de/aspose.slides/iautoshape)
* class [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)