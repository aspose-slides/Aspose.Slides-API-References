---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---


## show_legend_key property
Represents a specified chart's data label legend key display behavior. 
            True if the data label legend key is visible.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLegendKey property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLegendKey property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" cause to 
            all DataLabels[i].ShowLegendKey is equal to val).

### Definition:
```python
@property
def show_legend_key(self):
    ...
@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
