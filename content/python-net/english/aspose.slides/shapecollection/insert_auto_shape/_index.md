---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---


## insert_auto_shape {#int-asposeslidesshapetype-float-float-float-float}
Creates a new auto shape and inserts it into the shape collection at the specified index,
            applying default template formatting.

### Returns

The newly created [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the new auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |


## insert_auto_shape {#int-asposeslidesshapetype-float-float-float-float-bool}
Creates a new auto shape and inserts it into the shape collection at the specified index,
            optionally initializing it with default template styling.

### Returns

The newly created [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/aspose.slides/shapetype) of the auto shape to insert. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |
| create_from_template | **bool** | True to apply default template styling (including a non-empty name, simple style, and centered text); <br/><br/>            false to create the shape with all properties set to their defaults. |



### See Also
* class [`IAutoShape`](/slides/python-net/aspose.slides/iautoshape)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

