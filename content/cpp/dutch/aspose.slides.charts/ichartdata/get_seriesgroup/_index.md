---
title: get_SeriesGroup()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 222
url: /nl/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) methode




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) methode


Retourneert de groep van reeksen op de opgegeven index.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Opmerkingen


1) Elke groep van reeksen bevat reeksen met combineerbare typen. Groepen van combineerbare serietypen worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van reeksen reeksen die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus, het principe van het groeperen van reeksen is een groepering op basis van bovengenoemde typegroepen en op het type plotten (primaire/secundaire). 2) Een groep van reeksen bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke reeks in de groep (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](../../chartseriesgroup/) klasse is lezen/schrijven. Elke \"series group properties\" kan een alleen-lezen projectie hebben in de [ChartSeries](../../chartseries/) klasse. 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [IChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)