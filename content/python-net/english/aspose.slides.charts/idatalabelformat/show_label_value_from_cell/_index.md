---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---


## show_label_value_from_cell property
Represents a specified chart's data label cell value display behavior. 
            True displays cell value. False to hide.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLabelValueFromCell property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLabelValueFromCell property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" cause to 
            all DataLabels[i].ShowLabelValueFromCell is equal to val).

### Definition:
```python
@property
def show_label_value_from_cell(self):
    ...
@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
