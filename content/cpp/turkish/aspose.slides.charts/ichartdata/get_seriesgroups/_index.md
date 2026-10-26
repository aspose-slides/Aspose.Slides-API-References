---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API Referansı
description: Seri gruplarını alır. Salt okunur IChartSeriesGroupCollection.
type: docs
weight: 27
url: /tr/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metodu

Seri gruplarını alır. Salt okunur [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Açıklamalar

1) Her seri grubu, birleştirilebilir türlere sahip serileri içerir. Birleştirilebilir seri türleri grupları, CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde veya ikincil eksenlerde (her iki durumda aynı grup içinde değildir) çizilen serileri içerir. Bu nedenle, seri gruplandırma ilkesi, yukarıda belirtilen tür gruplarına ve birincil/ikincil çizim tipine göre bir gruplamadır.

2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini ("series group properties") içerir. [ChartSeriesGroup](../../chartseriesgroup/) sınıfındaki "Series group properties" okuma/yazma özelliğine sahiptir. "Series group properties" öğelerinin her biri, [ChartSeries](../../chartseries/) sınıfında salt okunur bir projeksiyona sahip olabilir.

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Sınıf [IChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)