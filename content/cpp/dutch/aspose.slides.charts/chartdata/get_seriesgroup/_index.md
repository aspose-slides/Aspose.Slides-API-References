---
title: get_SeriesGroup()
second_title: Aspose.Slides voor C++ API Referentie
description: 
type: docs
weight: 222
url: /nl/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) methode

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) methode

Retourneert de groep van series op de opgegeven index.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Opmerkingen

1) Elke groep van series bevat series met combineerbare types. Groepen van combineerbare serietypes zijn gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van series series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus het principe van het groeperen van series is een groepering op basis van bovengenoemde typegroepen en op primaire/secundaire plottype. 2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("eigenschappen van seriesgroep"). "eigenschappen van seriesgroep" in [ChartSeriesGroup](../../chartseriesgroup/) klasse is lezen/schrijven. Elke van de "eigenschappen van seriesgroep" kan een alleen-lezen projectie hebben in [ChartSeries](../../chartseries/) klasse.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)