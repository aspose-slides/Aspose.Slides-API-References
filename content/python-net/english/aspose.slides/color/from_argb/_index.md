---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/color/from_argb/
weight: 20
---


## from_argb(argb) {#int}
Creates a color from a 32-bit ARGB value.

### Returns

The color created from the specified value.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| argb | **int** | A value specifying the 32-bit ARGB value (signed or unsigned). |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, base_color) {#int-color}
Creates a color from the specified alpha value and base color.

### Returns

The color created from the specified values.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | The alpha component value. Valid values are 0 through 255. |
| base_color | [`Color`](/slides/python-net/aspose.slides/color) | The color from which to create the new color. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(red, green, blue) {#int-int-int}
Creates an opaque color (alpha is 255) from the specified red, green and blue values.

### Returns

The color created from the specified values.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| red | **int** | The red component value. Valid values are 0 through 255. |
| green | **int** | The green component value. Valid values are 0 through 255. |
| blue | **int** | The blue component value. Valid values are 0 through 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Creates a color from the four ARGB component (alpha, red, green, and blue) values.

### Returns

The color created from the specified values.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | The alpha component value. Valid values are 0 through 255. |
| red | **int** | The red component value. Valid values are 0 through 255. |
| green | **int** | The green component value. Valid values are 0 through 255. |
| blue | **int** | The blue component value. Valid values are 0 through 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |



### See Also
* class [`Color`](/slides/python-net/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

