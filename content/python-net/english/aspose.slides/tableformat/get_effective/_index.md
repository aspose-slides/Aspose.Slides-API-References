---
title: get_effective method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/tableformat/get_effective/
weight: 10
---


## get_effective {#}
Gets effective table formatting properties with inheritance and table styles applied.

### Returns

A [`ITableFormatEffectiveData`](/slides/python-net/aspose.slides/itableformateffectivedata).



```python
def get_effective(self):
    ...
```


### Examples

This example demonstrates getting effective fill format for different table logic parts.
            Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
            So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.



### See Also
* class [`ITableFormatEffectiveData`](/slides/python-net/aspose.slides/itableformateffectivedata)
* class [`TableFormat`](/slides/python-net/aspose.slides/tableformat)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

