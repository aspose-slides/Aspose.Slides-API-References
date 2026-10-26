---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups özelliği
Seri gruplarını alır.
            Salt-okunur [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection).

### Açıklamalar

1) Her seri grubu, birleştirilebilir türdeki serileri içerir. Birleştirilebilir seri tür grupları 
            CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır.
            Ayrıca her seri grubu, birincil eksen üzerinde ya da ikincil eksen üzerinde (aynı grupta iki durumda da değil) çizilen serileri içerir.
            Dolayısıyla, seri gruplandırma prensibi yukarıda bahsedilen tip grupları ve birincil/ikincil çizim türüne göre bir gruplamadır.
            
2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özellikleri içerir ("seri grup özellikleri").
"Seri grup özellikleri", ChartSeriesGroup sınıfında okunur/yazılabilir.
Her "seri grup özelliği", ChartSeries sınıfında salt-okunur bir projeksiyona sahip olabilir.

### Tanım:
```python
@property
def series_groups(self):
    ...
```

### İlgili
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* sınıf [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)