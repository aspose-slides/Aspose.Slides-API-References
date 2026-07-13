---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representeert de collectie van groepen van combineerbare series.
type: docs
url: /nl/com.aspose.slides/ichartseriesgroupcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Vertegenwoordigt de collectie van groepen van combineerbare reeksen.

--------------------

1) Elke groep van reeksen bevat reeksen met combineerbare typen. Groepen van combineerbare serietypen worden gedefinieerd en beschreven met de CombinableSeriesTypesGroup enum. Ook bevat elke groep van reeksen reeksen die worden geplot op primaire assen of op secundaire assen (niet beide gevallen in één groep). Het principe van het groeperen van reeksen is dus een groepering op basis van de hierboven genoemde typegroepen en op basis van het primaire/secundaire plottype. 2) Een groep van reeksen bevat enkele reeks-eigenschappen die gemeenschappelijk zijn voor elke reeks in de groep (“reeks-groepeigenschappen”). “Reeks-groepeigenschappen” in de ChartSeriesGroup-klasse is lees-schrijf. Elke “reeks-groepeigenschap” kan een alleen-lezen-projectie hebben in de ChartSeries-klasse.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Haalt de seriesgroep op basis van een reeks op. |
| [get_Item(int index)](#get-Item-int-) | Haalt de seriesgroep op basis van een index op. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Haalt de seriesgroep op basis van een reeks op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Retourwaarde:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Haalt de seriesgroep op basis van een index op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)