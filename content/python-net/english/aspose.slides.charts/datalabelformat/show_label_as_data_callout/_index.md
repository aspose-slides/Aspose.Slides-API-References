---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---


## show_label_as_data_callout property
Determines either specified chart's data label will be displayed as data callout or as data label.
            
            If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLabelAsDataCallout property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLabelAsDataCallout property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause to 
            all DataLabels[i].ShowLabelAsDataCallout is equal to val).

### Definition:
```python
@property
def show_label_as_data_callout(self):
    ...
@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```
