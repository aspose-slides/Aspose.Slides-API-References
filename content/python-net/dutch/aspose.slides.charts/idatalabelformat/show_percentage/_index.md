---
title: show_percentage property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage eigenschap
Represents a specified chart's data label percentage value display behavior. 
True displays the percentage value. False to hide.
Lezen/Schrijven **bool**.

### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
eigenschap gets or sets the default value of the ShowPercentage property for the new data 
labels in the DataLabelCollection collection.
Set this eigenschap with value also sets this value to the ShowPercentage property 
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
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)