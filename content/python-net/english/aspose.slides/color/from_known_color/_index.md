---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/color/from_known_color/
weight: 30
---


## from_known_color(known_color) {#knowncolor}
Creates a color from the specified predefined color.<br/>This is the only way to obtain a system color (such as `KnownColor.CONTROL`): system colors are not exposed as `Color` attributes because their values depend on the desktop theme, so they are read from the library runtime.

### Returns

The color that this method creates.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| known_color | **KnownColor** | An element of the `KnownColor` enumeration (an `IntEnum` mirroring .NET `System.Drawing.KnownColor`) or its integer value. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | The value is not a valid `KnownColor` member. |



### See Also
* class [`Color`](/slides/python-net/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

