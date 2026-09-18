---
title: position property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## konum özelliği
Represents the position of the data label.
            Okuma/Yazma [`LegendDataLabelPosition`](/slides/python-net/tr/aspose.slides.charts/legenddatalabelposition).

### Açıklamalar
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Position property for the new data 
            labels in the DataLabelCollection collection.
            Represents the position for the DataLabel objects.
            Set this property with value also sets this value to the Position property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" cause to 
            all DataLabels[i].Position is equal to val).

### Tanım:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* enumerasyon [`LegendDataLabelPosition`](/slides/python-net/tr/aspose.slides.charts/legenddatalabelposition)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)