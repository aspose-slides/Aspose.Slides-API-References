---
title: position property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/idatalabelformat/position/
weight: 90
---


## position property
Represents the position of the data label.
            Read/write [`LegendDataLabelPosition`](/slides/python-net/aspose.slides.charts/legenddatalabelposition).


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Position property for the new data 
            labels in the DataLabelCollection collection.
            Represents the position for the DataLabel objects.
            Set this property with value also sets this value to the Position property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" cause to 
            all DataLabels[i].Position is equal to val).

### Definition:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```


### See Also
* class [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat)
* enumeration [`LegendDataLabelPosition`](/slides/python-net/aspose.slides.charts/legenddatalabelposition)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

