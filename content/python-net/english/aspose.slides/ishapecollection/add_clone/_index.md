---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_clone/
weight: 60
---


## add_clone {#ishape}
Adds a copy of a specified shape to the end of the collection.
            X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the `
source_shape`
.

### Returns

New shape.



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | IShape | Shape to clone. |



## add_clone {#ishape-float-float}
Adds a copy of a specified shape to the end of the collection.
            Width and Height of the new shape are equal to Width and Height of the `
source_shape`
.

### Returns

New shape.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | IShape | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |



## add_clone {#ishape-float-float-float-float}
Adds a copy of a specified shape to the end of the collection.

### Returns

New shape.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | IShape | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |



### See Also
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
