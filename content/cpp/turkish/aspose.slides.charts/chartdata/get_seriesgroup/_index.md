---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 222
url: /tr/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) method

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) method

Belirtilen indeksdeki serilerin grubunu döndürür.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Açıklamalar

1) Her seri grubu, birleştirilebilir türlere sahip serileri içerir. Birleştirilebilir seri türleri grupları, **CombinableSeriesTypesGroup enum** ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde veya ikincil eksenlerde (aynı grup içinde iki durumda da değil) çizilen serileri içerir. Böylece seri gruplandırma prensibi, yukarıda bahsedilen tür gruplarına ve birincil/ikincil çizim tipine göre gruplayandır. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerine sahiptir ("seriler grup özellikleri"). "[ChartSeriesGroup](../../chartseriesgroup/)" sınıfındaki "seriler grup özellikleri" okuma/yazma olarak tanımlanmıştır. "Seriler grup özelliklerinin" her biri "[ChartSeries](../../chartseries/)" sınıfında yalnızca okuma olarak sunulabilir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartSeriesGroup](../../ichartseriesgroup/)
* Sınıf [IChartSeries](../../ichartseries/)
* Sınıf [ChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)