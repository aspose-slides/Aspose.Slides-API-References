---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---


## show_percentage property
Represents a specified chart's data label percentage value display behavior. 
            True displays the percentage value. False to hide.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowPercentage property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowPercentage property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" cause to 
            all DataLabels[i].ShowPercentage is equal to val).

### Definition:
```python
@property
def show_percentage(self):
    ...
@show_percentage.setter
def show_percentage(self, value):
    ...
```

### See Also
* class [`DataLabelFormat`](/slides/python-net/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
