---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_connector/
weight: 260
---


## insert_connector {#int-shapetype-float-float-float-float}
Creates a new Connector, tunes it from default template and inserts it to 
            the collection at the specified index.

### Returns

Created Connector object.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which value should be inserted. |
| shape_type | ShapeType | An [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |



## insert_connector {#int-shapetype-float-float-float-float-bool}
Creates a new Connector and inserts it to the collection at the specified index.

### Returns

Created Connector object.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which value should be inserted. |
| shape_type | ShapeType | An [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of shape. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| create_from_template | bool | If true then new shape will be tuned from default template. Not empty name, <br/><br/>            simple style, text centered will be assined to the new shape.<br/><br/>            If false then all values of the properties of the new shape will have default values. |



### See Also
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
