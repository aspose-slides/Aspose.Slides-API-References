---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_clone/
weight: 250
---


## insert_clone {#int-ishape}
Creates a copy of the specified shape and inserts it into the shape collection at the specified index.
            The cloned shape retains the original’s position and size.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the cloned shape. |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to clone. |


## insert_clone {#int-ishape-float-float}
Creates a copy of the specified shape and inserts it into the shape collection at the specified index.
            The new shape retains the width and height of the `source_shape`.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the cloned shape. |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to clone. |
| x | **float** | The x-coordinate of the cloned shape’s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape’s frame, in points. |


## insert_clone {#int-ishape-float-float-float-float}
Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

### Returns

The newly created [`IShape`](/slides/python-net/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the cloned shape. |
| source_shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to clone. |
| x | **float** | The x-coordinate of the cloned shape’s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape’s frame, in points. |
| width | **float** | The width of the cloned shape’s frame, in points. |
| height | **float** | The height of the cloned shape’s frame, in points. |



### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

