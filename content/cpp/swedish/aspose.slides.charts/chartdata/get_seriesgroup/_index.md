---
title: get_SeriesGroup()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 222
url: /sv/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metod

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metod

Returnerar gruppen av serier på det angivna indexet.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Anmärkningar

1) Varje seriegrupp innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med CombinableSeriesTypesGroup-enum. Dessutom innehåller varje seriegrupp serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i en grupp). Så är principen för seriegroupering en gruppering efter de ovan nämnda typgrupperna och efter primär/sekundär plottningstyp. 2) En seriegrupp innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper"). "Seriegruppsegenskaper" i [ChartSeriesGroup](../../chartseriesgroup/) klass är läs/skriv. Varje av "seriegruppsegenskaper" kan ha en skrivskyddad projection i [ChartSeries](../../chartseries/) klass.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartSeriesGroup](../../ichartseriesgroup/)
* Klass [IChartSeries](../../ichartseries/)
* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)