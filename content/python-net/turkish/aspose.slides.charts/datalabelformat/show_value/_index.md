---
title: show_value property
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value özelliği
Represents a specified chart's data label percentage value display behavior. 
            True yüzde değerini gösterir. False gizler.
            Okunur/Yazılır **bool**.

### Açıklamalar

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowValue Özelliği for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowValue Özelliği 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" tüm DataLabels[i].ShowValue değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)