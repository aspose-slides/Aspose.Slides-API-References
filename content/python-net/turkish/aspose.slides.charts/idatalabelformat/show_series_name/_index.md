---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name özelliği
Bir grafikte veri etiketlerinin seri adını gösterme davranışını belirten Boolean değeri döndürür veya ayarlar. 
            True serinin adını gösterir. False gizler.
            Okunabilir/yazılabilir **bool**.

### Açıklamalar

Bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise bu
            özellik, DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar.
            Bu özelliği bir değerle ayarlamak aynı zamanda DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowSeriesName özelliğini de bu değere ayarlar
            (yani "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" tüm DataLabels[i].ShowSeriesName değerini val yapar).

### Tanım:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### İlgili
* class [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)