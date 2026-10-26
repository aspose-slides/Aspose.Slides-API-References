---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key özelliği
Belirtilen bir grafiğin veri etiketi açıklama anahtarı gösterim davranışını temsil eder. 
True if the data label legend key is visible.
Okunur/yazılır **bool**.

### Açıklamalar

Bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar.  
Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLegendKey özelliğine de ayarlar (örn. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" tüm DataLabels[i].ShowLegendKey değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### İlgili
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)