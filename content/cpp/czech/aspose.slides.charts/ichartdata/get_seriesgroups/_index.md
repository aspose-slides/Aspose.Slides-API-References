---
title: get_SeriesGroups()
second_title: Aspose.Slides pro C++ - referenční API
description: Získá skupiny series. Pouze ke čtení IChartSeriesGroupCollection.
type: docs
weight: 27
url: /cs/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metoda

Získá skupiny series. Pouze ke čtení [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Poznámky

1) Každá skupina series obsahuje series s kombinovatelnými typy. Skupiny kombinovatelných typů series jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup. Také každá skupina series obsahuje series, které jsou vykresleny buď na primárních osách, nebo na sekundárních osách (ne oba případy v jedné skupině). Princip seskupování series tedy spočívá ve skupování podle výše zmíněných typových skupin a podle typu vykreslování (primární/sekundární).

2) Skupina series obsahuje některé vlastnosti series, které jsou společné pro každou series ve skupině („series group properties“). „Series group properties“ ve třídě [ChartSeriesGroup](../../chartseriesgroup/) jsou čtení/zápis. Každá z „series group properties“ může mít projekci pouze ke čtení ve třídě [ChartSeries](../../chartseries/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Třída [IChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)