---
title: portion_format property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/portion/portion_format/
weight: 90
---


## portion_format property
Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied.
            Read-only [`IPortionFormat`](/slides/python-net/aspose.slides/iportionformat).


### Remarks

The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.


In order to get the effective values including inherited ones use the [`PortionFormat.get_effective`](/slides/python-net/aspose.slides/portionformat/get_effective) method.

### Definition:
```python
@property
def portion_format(self):
    ...
```
