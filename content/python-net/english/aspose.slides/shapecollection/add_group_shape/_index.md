---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_group_shape/
weight: 80
---


## add_group_shape {#}
Creates a new empty group shape and adds it to the end of the shape collection.
            The group’s frame will automatically adjust to fit any shapes added to it.

### Returns

The newly created [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```


### Examples

The following example shows how to add a group shape to a slide of PowerPoint Presentation.


## add_group_shape {#isvgimage-float-float-float-float}
Creates a new group shape, converts the specified SVG image into individual shapes,
            and adds the resulting group to the end of the shape collection.

### Returns

The newly created [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) | The [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) containing vector content to convert into shapes. |
| x | **float** | The x-coordinate of the group’s frame, in points. |
| y | **float** | The y-coordinate of the group’s frame, in points. |
| width | **float** | The width of the group’s frame, in points. |
| height | **float** | The height of the group’s frame, in points. |



### See Also
* class [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)
* class [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

