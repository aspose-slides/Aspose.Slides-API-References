---
title: show_value property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---


## show_value property
Represents a specified chart's data label percentage value display behavior. 
            True displays the percentage value. False to hide.
            Read/write .NET type System.Boolean.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowValue property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowValue property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
            all DataLabels[i].ShowValue is equal to val).

### Definition:
```python
@property
def show_value(self):
    ...
@show_value.setter
def show_value(self, value):
    ...
```
