---
title: from_name method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/color/from_name/
weight: 40
---


## from_name(name) {#str}
Creates a color from the specified name of a predefined color.<br/>The lookup is case-insensitive and ignores underscores and spaces: `"LightBlue"`, `"lightblue"` and `"light_blue"` all resolve to `Color.light_blue`. See the [`Color`](/slides/python-net/aspose.slides/color) class page for the list of predefined colors.

### Returns

The named color.



```python
@staticmethod
def from_name(name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | **str** | A string that is the name of a predefined color. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | The name is not a name of a predefined color. |
| **TypeError** | The name is not a string. |



### See Also
* class [`Color`](/slides/python-net/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

