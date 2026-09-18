---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key tulajdonság
Represents a specified chart's data label legend key display behavior. 
            True if the data label legend key is visible.
            Olvasás/írás **bool**.

### Megjegyzés

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            tulajdonság gets or sets the default value of the ShowLegendKey tulajdonság for the new data 
            labels in the DataLabelCollection collection.
            Set this tulajdonság with value also sets this value to the ShowLegendKey tulajdonság 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" cause to 
            all DataLabels[i].ShowLegendKey is equal to val).

### Definíció:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)