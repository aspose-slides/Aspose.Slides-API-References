---
title: get_SeriesGroups()
second_title: Aspose.Slides pro C++ API Reference
description: Získá skupiny sérií. Pouze pro čtení IChartSeriesGroupCollection.
type: docs
weight: 27
url: /cs/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() method

Získá skupiny sérií. Pouze pro čtení [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Poznámky

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny kombinovatelných typů sérií jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup. Také každá skupina sérií obsahuje série, které jsou vykresleny buď na primárních osách, nebo na sekundárních osách (ne v obou případech v jedné skupině). Princip seskupování sérií tedy spočívá ve skupinování podle výše zmíněných typových skupin a podle typu vykreslení na primární/sekundární osu.

2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině ("series group properties"). "Series group properties" ve třídě [ChartSeriesGroup](../../chartseriesgroup/) je čtení/zápis. Každá z "series group properties" může mít projekci pouze pro čtení ve třídě [ChartSeries](../../chartseries/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Třída [ChartData](../)
* Prostor názvů [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)