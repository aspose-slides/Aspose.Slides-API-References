---
title: contains method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/rectangle/contains/
weight: 20
---


## contains(self, point) {#point}
Determines if the specified point is contained within this rectangle.

### Returns

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/aspose.slides/point) | The point to test. Any object with `x` and `y` attributes is accepted. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectangle}
Determines if the rectangular region represented by `rect` is entirely contained within this rectangle.

### Returns

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/aspose.slides/rectangle) | The rectangle to test. Any object with `x`, `y`, `width` and `height` attributes is accepted. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#int-int}
Determines if the specified point is contained within this rectangle.

### Returns

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **int** | The x-coordinate of the point to test. |
| y | **int** | The y-coordinate of the point to test. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### See Also
* class [`Point`](/slides/python-net/aspose.slides/point)
* class [`Rectangle`](/slides/python-net/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

