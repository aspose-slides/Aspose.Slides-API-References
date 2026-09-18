---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage özelliği
Belirtilen bir grafiğin veri etiketi yüzde değeri görüntüleme davranışını temsil eder. 
True yüzde değerini gösterir. False gizlemek için.
Okuma/Yazma **bool**.

### Açıklamalar

Eğer bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda tüm DataLabelCollection koleksiyonundaki veri etiketleri için ShowPercentage özelliğine bu değeri atar (i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" tüm DataLabels[i].ShowPercentage değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)