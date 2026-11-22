---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups özelliği
Seri gruplarını alır.
Salt okunur [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection).

### Açıklamalar

1) Her seri grubu, birleştirilebilir türlerdeki serileri içerir. Birleştirilebilir seri türleri grupları, CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde ya da ikincil eksenlerde (aynı grupta her iki durumda da değil) çizilen serileri içerir. Bu nedenle seri gruplama prensibi, yukarıda belirtilen tür gruplarına ve birincil/ikincil çizim tipine göre gruplamadır.

2) Seri grubu, gruptaki her seri için ortak olan bazı seri properies içerir ("series group properties"). ChartSeriesGroup sınıfındaki "Series group properties" okuma/yazma özelliğine sahiptir. "Series group properties" öğelerinin her biri ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

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