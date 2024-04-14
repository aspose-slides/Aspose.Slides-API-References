---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_connector/
weight: 70
---


## add_connector {#shapetype-float-float-float-float}
Creates a new Connector, tunes it from default template and adds it to the end of the collection.

### Returns

The zero-based index of the created shape.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | ShapeType | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |



## add_connector {#shapetype-float-float-float-float-bool}
Creates a new Connector and adds it to the end of the collection.

### Returns

The zero-based index of the created shape.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
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



