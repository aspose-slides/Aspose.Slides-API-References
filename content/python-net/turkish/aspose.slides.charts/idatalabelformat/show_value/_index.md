---
title: show_value property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value özelliği
Belirli bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder.
True yüzde değerini gösterir. False gizlemek için.
Okuma/yazma **bool**.

### Açıklamalar

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise bu özellik, DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowValue özelliğinin varsayılan değerini alır veya ayarlar.
Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowValue özelliğine de ayarlar.
(ör. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" tüm DataLabels[i].ShowValue'in val'e eşit olmasına neden olur.)

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
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)