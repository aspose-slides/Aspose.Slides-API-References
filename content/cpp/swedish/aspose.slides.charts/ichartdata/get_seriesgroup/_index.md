---
title: get_SeriesGroup()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 222
url: /sv/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metod

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metod

Returnerar gruppen av serier på det angivna indexet.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Anmärkningar

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enumen CombinableSeriesTypesGroup. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i samma grupp). Så principen för seriegruppering är en gruppering efter de ovan nämnda typgrupperna och efter primär/sekundär plottningstyp. 2) Grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen (\"series group properties\"). \"Series group properties\" i [ChartSeriesGroup](../../chartseriesgroup/) klass är läs/skriv. Varje av \"series group properties\" kan ha en skrivskyddad projektion i [ChartSeries](../../chartseries/) klass.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartSeriesGroup](../../ichartseriesgroup/)
* Klass [IChartSeries](../../ichartseries/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)