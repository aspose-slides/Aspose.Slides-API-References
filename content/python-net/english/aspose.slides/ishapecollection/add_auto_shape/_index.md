---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---


## add_auto_shape {#asposeslidesshapetype-float-float-float-float}
Creates a new auto shape with default formatting and adds it to the end of the
            shape collection.

### Returns

The newly created [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |


## add_auto_shape {#asposeslidesshapetype-float-float-float-float-bool}
Creates a new auto shape and adds it to the end of the shape collection, optionally
            initializing it with default template formatting.

### Returns

The newly created [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |
| create_from_template | **bool** | True to apply default template styling (simple style, centered text, and non-empty name)<br/><br/>            to the new shape; false to create the shape with all properties set to their default values. |



### See Also
* class [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

