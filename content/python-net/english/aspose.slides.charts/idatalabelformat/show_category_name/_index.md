---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/show_category_name/
weight: 80
---


## show_category_name property
Represents a specified chart's data label category name display behavior.
            True to display the category name for the data labels on a chart. False to hide.
            Read/write **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).

### Definition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### See Also
* class [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

