---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API Referansı
description: Serileri gruplarını alır. Yalnızca okunabilir IChartSeriesGroupCollection.
type: docs
weight: 27
url: /tr/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() yöntemi

Seri gruplarını alır. Yalnızca okunabilir [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Açıklamalar

1) Her bir seri grubu, birleşebilir tiplerdeki serileri içerir. Birleşebilir seri tiplerinin grupları, CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her bir seri grubu, serilerin birincil eksenlerde mi yoksa ikincil eksenlerde mi çizildiğini (bir grup içinde her iki durumda da bulunmaz) içerir. Dolayısıyla, seri gruplandırma ilkesi, yukarıda bahsedilen tip gruplarına ve birincil/ikincil çizim tipine göre bir gruplamadır.

2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini ("seri grup özellikleri") içerir. [ChartSeriesGroup](../../chartseriesgroup/) sınıfındaki "Seri grup özellikleri" okuma/yazma olarak tanımlıdır. "Seri grup özellikleri"nin her biri, [ChartSeries](../../chartseries/) sınıfında yalnızca okunabilir bir projeksiyona sahip olabilir.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Sınıf [ChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)