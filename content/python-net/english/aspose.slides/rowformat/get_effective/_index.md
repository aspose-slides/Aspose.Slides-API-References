---
title: get_effective method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/rowformat/get_effective/
weight: 10
---


## get_effective {#}
Gets effective table row formatting properties with inheritance and table styles applied.

### Returns

A [`IRowFormatEffectiveData`](/slides/python-net/aspose.slides/irowformateffectivedata).



```python
def get_effective(self):
    ...
```


### Examples

This example demonstrates getting effective fill format for different table logic parts.
            Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
            So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.



### See Also
* class [`IRowFormatEffectiveData`](/slides/python-net/aspose.slides/irowformateffectivedata)
* class [`RowFormat`](/slides/python-net/aspose.slides/rowformat)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

