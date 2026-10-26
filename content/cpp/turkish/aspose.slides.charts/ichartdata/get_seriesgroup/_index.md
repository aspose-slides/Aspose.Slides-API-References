---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 222
url: /tr/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metot




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metot

Belirtilen indeksteki seri grubunu döndürür.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Açıklamalar

1) Her seri grubu, birleştirilebilir tipteki serileri içerir. Birleştirilebilir seri tiplerinin grupları, CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde ya da ikincil eksenlerde çizilen serileri içerir (aynı grup içinde her iki durumda da olmaz). Dolayısıyla, seri gruplama prensibi, yukarıda belirtilen tip gruplarına ve birincil/ikincil çizim tipine göre bir gruplamadır. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir (\"seri grup özellikleri\"). \"Seri grup özellikleri\" [ChartSeriesGroup](../../chartseriesgroup/) sınıfında okunur/yazılabilir. Her \"seri grup özelliği\" [ChartSeries](../../chartseries/) sınıfında yalnızca okunur bir projeksiyona sahip olabilir.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartSeriesGroup](../../ichartseriesgroup/)
* Sınıf [IChartSeries](../../ichartseries/)
* Sınıf [IChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)