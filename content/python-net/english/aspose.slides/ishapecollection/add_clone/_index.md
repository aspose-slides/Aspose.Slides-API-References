﻿---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_clone/
weight: 60
---


## add_clone {#ishape}
Creates a copy of the specified shape and adds it to the end of the shape collection.
            The cloned shape retains the original’s position and size.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to clone. |


## add_clone {#ishape-float-float}
Creates a copy of the specified shape and adds it to the end of the shape collection.
            The new shape retains the width and height of the `source_shape`.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to clone. |
| x | **float** | The x-coordinate of the cloned shape’s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape’s frame, in points. |


## add_clone {#ishape-float-float-float-float}
Creates a copy of the specified shape and adds it to the end of the shape collection.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The shape to clone. |
| x | **float** | The x-coordinate of the cloned shape’s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape’s frame, in points. |
| width | **float** | The width of the cloned shape’s frame, in points. |
| height | **float** | The height of the cloned shape’s frame, in points. |



### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

