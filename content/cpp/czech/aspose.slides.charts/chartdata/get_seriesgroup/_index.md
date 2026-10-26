---
title: get_SeriesGroup()
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 222
url: /cs/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metoda




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metoda


Vrací skupinu řad na zadaném indexu.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Poznámky


1) Každá skupina řad obsahuje řady s kombinovatelnými typy. Skupiny kombinovatelných typů řad jsou definovány a popsány výčtem CombinableSeriesTypesGroup. Také každá skupina řad obsahuje řady, které jsou vykreslovány buď na hlavních osách, nebo na vedlejších osách (ne v obou případech ve stejné skupině). Princip seskupování řad tedy spočívá ve skupinování podle výše zmíněných typových skupin a podle typu vykreslování – hlavní/vedlejší. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ ve třídě [ChartSeriesGroup](../../chartseriesgroup/) jsou čtení/zápis. Každá z „vlastností skupiny řad“ může mít v třídě [ChartSeries](../../chartseries/) jen pro čtení projekci. 
## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IChartSeriesGroup](../../ichartseriesgroup/)
* Třída [IChartSeries](../../ichartseries/)
* Třída [ChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)