---
title: separator property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/separator/
weight: 110
---


## separator property
Sets or returns a Variant representing the separator used for the data labels on a chart.
            Read/write **str**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Separator property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the Separator property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to 
            all DataLabels[i].Separator is equal to val).

### Definition:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### See Also
* class [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

