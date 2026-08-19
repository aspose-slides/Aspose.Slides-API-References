---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de verzameling van groepen van combineerbare series voor.
type: docs
url: /nl/com.aspose.slides/ichartseriesgroupcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Stelt de verzameling van groepen van combineerbare series voor.

--------------------

1) Elke groep van series bevat series met combineerbare types. Groepen van combineerbare serietypes worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van series series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Het principe van het groeperen van series is dus een groepering op basis van de hierboven genoemde typegroepen en op het type plotten (primaire/secundaire).  
2) Een groep van series bevat enkele serie-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("seriegroep-eigenschappen"). "Seriegroep-eigenschappen" in de klasse ChartSeriesGroup zijn lezen/schrijven. Elk van de "seriegroep-eigenschappen" kan een alleen-lezen projectie hebben in de klasse ChartSeries.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Haalt de seriegroep op op basis van een serie. |
| [get_Item(int index)](#get-Item-int-) | Haalt de seriegroep op op basis van een index. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Haalt de seriegroep op op basis van een serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Retour:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Haalt de seriegroep op op basis van een index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)