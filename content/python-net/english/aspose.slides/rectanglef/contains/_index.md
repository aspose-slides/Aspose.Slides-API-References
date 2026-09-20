---
title: contains method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/rectanglef/contains/
weight: 20
---


## contains(self, point) {#pointf}
Determines if the specified point is contained within this rectangle.

### Returns

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/aspose.slides/pointf) | The point to test. Any object with `x` and `y` attributes is accepted. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectanglef}
Determines if the rectangular region represented by `rect` is entirely contained within this rectangle.

### Returns

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/aspose.slides/rectanglef) | The rectangle to test. Any object with `x`, `y`, `width` and `height` attributes is accepted. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#float-float}
Determines if the specified point is contained within this rectangle.

### Returns

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the point to test. |
| y | **float** | The y-coordinate of the point to test. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### See Also
* class [`PointF`](/slides/python-net/aspose.slides/pointf)
* class [`RectangleF`](/slides/python-net/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

