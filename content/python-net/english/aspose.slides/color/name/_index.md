---
title: name property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/color/name/
weight: 190
---


## name property
Gets the name of this color.<br/>            For a named color (a named constant such as `Color.red`, or a color created with [`from_name`](/slides/python-net/aspose.slides/color/from_name/)) the .NET name is returned, e.g. `"Red"` or `"LightBlue"`.<br/>            For any other color the ARGB value is returned as lowercase hexadecimal without zero padding, e.g. `"ffff0000"`. `Color.empty.name` is `"0"`.
            Read-only **str**.

### Definition:
```python
@property
def name(self):
    ...
```


### See Also
* class [`Color`](/slides/python-net/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

