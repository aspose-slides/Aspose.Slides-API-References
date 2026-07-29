---
title: get_SeriesGroups()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar grupperna av serier. Skrivskyddad IChartSeriesGroupCollection.
type: docs
weight: 27
url: /sv/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metod


Hämtar grupperna av serier. Skrivskyddad [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Anmärkningar


1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med CombinableSeriesTypesGroup enum. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i samma grupp). Så är principen för seriegroupering en gruppering efter de ovan nämnda typgrupperna och efter primär/sekundär plottningstyp.

2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i [ChartSeriesGroup](../../chartseriesgroup/) klass är Läs/skriv. Varje av "series group properties" kan ha en skrivskyddad projektion i [ChartSeries](../../chartseries/) klass. 
## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)