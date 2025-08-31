---
title: number_format property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/number_format/
weight: 40
---


## number_format property
Represents the format string for the DataLabels object.
            Read/write **str**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
            property gets or sets the default value of the NumberFormat property for the new data 
            labels in the DataLabelCollection collection.
            When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### Definition:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### See Also
* class [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

