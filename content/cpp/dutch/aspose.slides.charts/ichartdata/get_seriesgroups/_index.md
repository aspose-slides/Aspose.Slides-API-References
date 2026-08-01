---
title: get_SeriesGroups()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de groepen van series op. Alleen-lezen IChartSeriesGroupCollection.
type: docs
weight: 27
url: /nl/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() methode

Haalt de groepen van series op. Alleen-lezen [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Opmerkingen

1) Elke groep van series bevat series met combineerbare types. Groepen van combineerbare serietypes worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van series series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus het principe van seriegroepering is een groepering op basis van de hierboven genoemde typegroepen en op primair/secundair plottype.

2) Een groep van series bevat enkele serie-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](../../chartseriesgroup/) klasse is lezen/schrijven. Elke \"series group properties\" kan een alleen-lezen projectie hebben in [ChartSeries](../../chartseries/) klasse.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klasse [IChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)