---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key özelliği
Belirtilen bir grafiğin veri etiketi açıklama anahtarı görüntüleme davranışını temsil eder. 
True if the data label legend key is visible.
Okuma/yazma **bool**.

### Açıklamalar

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özelliği DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar.  
Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLegendKey özelliğine de atar (ör. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" tüm DataLabels[i].ShowLegendKey değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Bakınız
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)