---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_group_shape/
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
| svg_image | ISvgImage | Svg image object [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) |
| x | float | The X coordinate for the left side of the shape group frame. |
| y | float | The Y coordinate for the top side of the shape group frame. |
| width | float | The width of the group of the shape group frame. |
| height | float | The height of a group of the shape group frame. |



