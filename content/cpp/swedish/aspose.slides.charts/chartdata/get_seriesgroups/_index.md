---
title: get_SeriesGroups()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar grupperna av serier. Skrivskyddad IChartSeriesGroupCollection.
type: docs
weight: 27
url: /sv/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() metod

Hämtar grupperna av serier. Skrivskyddad [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Anmärkningar

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivas med CombinableSeriesTypesGroup enum. Dessutom innehåller varje grupp av serier serier som plottas på antingen primära axlar eller sekundära axlar (inte båda fallen i samma grupp). Således är principen för seriegroupering en gruppering enligt de ovan nämnda typgrupperna samt efter primär/sekundär plottningstyp.

2) En grupp av serier innehåller några serieegenskaper som är gemensamma för varje serie i gruppen (\"seriegruppsegenskaper\"). \"Seriegruppsegenskaper\" i [ChartSeriesGroup](../../chartseriesgroup/) klass är läs/skriv. Varje av \"seriegruppsegenskaper\" kan ha en skrivskyddad projektion i [ChartSeries](../../chartseries/) klass.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)