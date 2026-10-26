---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection klasse

Stelt de collectie van groepen van combineerbare series voor.

Het IChartSeriesGroupCollection type exposeert de volgende leden:

Haalt de seriesgroep op basis van index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Opmerkingen

1) Elke groep van series bevat series met combineerbare types. Groepen van 
            combineerbare serietypes zijn gedefinieerd en beschreven met de CombinableSeriesTypesGroup 
            enum.
            Ook bevat elke groep van series series die worden geplot ofwel 
            op primaire assen of op secundaire assen (niet beide gevallen in één groep).
            Dus, het principe van seriesgroepering is een groepering op basis van de hierboven genoemde typegroepen 
            en op primair/secundair plottype.
            
            2) Een groep van series bevat enkele serieseigenschappen die gemeenschappelijk zijn voor 
            elke serie in de groep (“series group properties”).
            “Series group properties” in de ChartSeriesGroup class is lezen/schrijven.
            Elke “series group properties” kan een alleen-lezen projectie hebben in de ChartSeries class.


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)