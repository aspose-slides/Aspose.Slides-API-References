---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size özelliği
Belirtilen bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. 
            True balon boyutu değerini gösterir. False gizler.
            Okuma/yazma **bool**.


### Açıklamalar

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            özelliği yeni veri 
            etiketleri için ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar.
            Set this property with value also sets this value to the ShowBubbleSize property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to 
            all DataLabels[i].ShowBubbleSize is equal to val).

### Tanım:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)