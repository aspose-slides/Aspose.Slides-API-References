---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---


## show_bubble_size property
Represents a specified chart's data label bubble size value display behavior. 
            True displays the bubble size value. False to hide.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowBubbleSize property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowBubbleSize property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to 
            all DataLabels[i].ShowBubbleSize is equal to val).

### Definition:
```python
@property
def show_bubble_size(self):
    ...
@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### See Also
* class [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
