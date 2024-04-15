---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_auto_shape/
weight: 40
---


## add_auto_shape {#shapetype-float-float-float-float}
Creates a new AutoShape, tunes it from default template and adds it to the end of the collection.

### Returns

Created AutoShape object.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | ShapeType | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |



## add_auto_shape {#shapetype-float-float-float-float-bool}
Creates a new AutoShape and adds it to the end of the collection.

### Returns

Created AutoShape object.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | ShapeType | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| create_from_template | bool | If true then new shape will be tuned from default template. Not empty name, <br/><br/>            simple style, text centered will be assined to the new shape.<br/><br/>            If false then all values of the properties of the new shape will have default values. |



### See Also
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
