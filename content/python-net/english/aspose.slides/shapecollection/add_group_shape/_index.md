﻿---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_group_shape/
weight: 80
---


## add_group_shape {#}
Creates a new GroupShape and adds it to the end of the collection.
            GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.

### Returns

Created GroupShape object.



```python
def add_group_shape(self):
    ...
```


### Examples

The following example shows how to add a group shape to a slide of PowerPoint Presentation.


## add_group_shape {#isvgimage-float-float-float-float}
Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection.

### Returns

Created GroupShape object.



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) | Svg image object [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) |
| x | **float** | The X coordinate for the left side of the shape group frame. |
| y | **float** | The Y coordinate for the top side of the shape group frame. |
| width | **float** | The width of the group of the shape group frame. |
| height | **float** | The height of a group of the shape group frame. |



### See Also
* class [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)
* class [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

