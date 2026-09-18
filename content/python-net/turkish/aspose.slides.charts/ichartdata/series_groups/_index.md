---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups özelliği
Seri gruplarını getirir.
Salt okunur [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection).

### Açıklamalar

1) Her seri grubu, birleştirilebilir türlerdeki serileri içerir. Birleştirilebilir seri türleri grupları, CombinableSeriesTypesGroup enum ile tanımlanmış ve açıklanmıştır.
    Ayrıca, her seri grubu, birincil eksenlerde ya da ikincil eksenlerde (aynı grup içinde her iki durumda da değil) çizilen serileri içerir.
    Dolayısıyla, seri gruplandırma prensibi, yukarıda belirtilen tür grupları ve birincil/ikincil çizim türüne göre bir gruplaştırmadır.

2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özellikleri içerir ("Seri grup özellikleri").
    "Seri grup özellikleri" ChartSeriesGroup sınıfında okunabilir/yazılabilir.
    Her "Seri grup özellikleri" ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

### Tanım:
```python
@property
def series_groups(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* sınıf [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)