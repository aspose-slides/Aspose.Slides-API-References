---
title: show_label_value_from_cell property
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell özelliği
Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. 
True hücre değerini gösterir. False gizler.
Okunur/Yazılabilir **bool**.

### Açıklamalar
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
property gets or sets the default value of the ShowLabelValueFromCell property for the new data 
labels in the DataLabelCollection collection.
Set this property with value also sets this value to the ShowLabelValueFromCell property 
for all data labels in the DataLabelCollection collection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" cause to 
all DataLabels[i].ShowLabelValueFromCell is equal to val).

### Tanım:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)