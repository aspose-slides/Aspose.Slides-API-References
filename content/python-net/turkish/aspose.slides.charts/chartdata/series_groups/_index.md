---
title: series_groups property
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups özelliği
Seri gruplarını alır.
            Yalnızca okunabilir [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection).


### Açıklamalar

1) Her seri grubu, birleştirilebilir tiplerdeki serileri içerir. Groups of 
            birleştirilebilir seri tipleri tanımlanmış ve CombinableSeriesTypesGroup 
            enum ile açıklanmıştır.
            Ayrıca her seri grubu, birincil eksenlerde veya ikincil eksenlerde (aynı grupta her iki durumda da değil) çizilen serileri içerir.
            Dolayısıyla, seri gruplandırma ilkesi, yukarıda belirtilen tip gruplarına ve birincil/ikincil çizim tipine göre bir gruplamadır.
            
            2) Grup içindeki seriler, grup içindeki her seri için ortak bazı seri özelliklerine sahiptir ("seri grup özellikleri").
            ChartSeriesGroup sınıfındaki "Series group properties" okuma/yazma özelliğine sahiptir.
            "Series group properties" öğelerinin her biri, ChartSeries sınıfında yalnızca okunabilir bir projeksiyona sahip olabilir.

### Tanım:
```python
@property
def series_groups(self):
    ...
```


### Ayrıca Bakınız
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* sınıf [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)