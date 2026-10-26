---
title: get_SeriesGroup()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 222
url: /cs/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metoda




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metoda

Vrátí skupinu sérií na zadaném indexu.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Poznámky

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny kombinovatelných typů sérií jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup. Také každá skupina sérií obsahuje série, které jsou vykreslovány buď na primárních osách, nebo na sekundárních osách (nikoli v obou případech v jedné skupině). Princip seskupování sérií je tedy seskupování podle výše uvedených typových skupin a podle typu vykreslování (primární/sekundární). 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině ("series group properties"). "Series group properties" ve třídě [ChartSeriesGroup](../../chartseriesgroup/) jsou čtení/zápis. Každá z "series group properties" může mít projekci jen pro čtení ve třídě [ChartSeries](../../chartseries/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)