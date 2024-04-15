---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_clone/
weight: 250
---


## insert_clone {#int-ishape}
Inserts a copy of a specified shape to specified position of the collection.
            X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the `
source_shape`
.

### Returns

Inserted shape.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new shape. |
| source_shape | IShape | Shape to clone. |



## insert_clone {#int-ishape-float-float}
Inserts a copy of a specified shape to specified position of the collection.
            Width and Height of the new shape are equal to Width and Height of the `
source_shape`
.

### Returns

Inserted shape.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new shape. |
| source_shape | IShape | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |



## insert_clone {#int-ishape-float-float-float-float}
Inserts a copy of a specified shape to specified position of the collection.

### Returns

Inserted shape.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new shape. |
| source_shape | IShape | Shape to clone. |
| x | float | X coordinate of a new shape. |
| y | float | Y coordinate of a new shape. |
| width | float | Width of a new shape. |
| height | float | Height of a new shape. |



### See Also
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
