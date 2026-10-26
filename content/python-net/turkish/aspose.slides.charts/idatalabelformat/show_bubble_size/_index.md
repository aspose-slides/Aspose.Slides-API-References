---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size özelliği
Belirli bir grafiğin veri etiketi balon boyutu değeri gösterim davranışını temsil eder.
            True balon boyutu değerini gösterir. False gizler.
            Okunur/yazılır **bool**.

### Açıklamalar

Eğer bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar.
Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowBubbleSize özelliğine de ayarlar.
(ör. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" tüm DataLabels[i].ShowBubbleSize değerini val yapar.)

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
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)