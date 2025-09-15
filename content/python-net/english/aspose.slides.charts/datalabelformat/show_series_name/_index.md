---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---


## show_series_name property
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True to show the series name. False to hide.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowSeriesName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowSeriesName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            all DataLabels[i].ShowSeriesName is equal to val).

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### See Also
* class [`DataLabelFormat`](/slides/python-net/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

