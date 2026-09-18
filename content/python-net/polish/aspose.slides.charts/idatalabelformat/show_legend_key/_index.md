---
title: show_legend_key property
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key property
Represents a specified chart's data label legend key display behavior. 
            True if the data label legend key is visible.
            Read/write **bool**.

### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLegendKey property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLegendKey property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" cause to 
            all DataLabels[i].ShowLegendKey is equal to val).

### Definicja:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)