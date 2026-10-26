---
title: get_TrendLines()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Kolekcja linii trendu serii. Tylko do odczytu ITrendlineCollection.
type: docs
weight: 209
url: /pl/aspose.slides.charts/chartseries/get_trendlines/
---
## ChartSeries::get_TrendLines() metoda

Kolekcja linii trendu serii. tylko do odczytu [ITrendlineCollection](../../itrendlinecollection/).

```cpp
System::SharedPtr<ITrendlineCollection> Aspose::Slides::Charts::ChartSeries::get_TrendLines() override
```

## Uwagi

TrendLines są dostępne (nie null) dla serii danych w nieukładanych 2-D area, bar, column, line, stock, xy (scatter) i bubble charts. trendline nie jest dostępna dla serii danych w żadnym typie wykresu, który jest stacked lub 3-D. Trendlines nie są również dostępne dla radar, pie, surface lub doughnut charts.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITrendlineCollection](../../itrendlinecollection/)
* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)