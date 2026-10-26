---
title: series_groups property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups eigenschap
Haalt de groepen van series op.
            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection).

### Opmerkingen

1) Elke seriegroep bevat series met combineerbare typen. Groepen van 
            combineerbare serietypen worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup 
            enum.
            Ook bevat elke seriegroep series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep).
            Dus is het principe van seriegroepering een groepering op basis van de hierboven genoemde typegroepen en op het type plotten (primair/secundair).

2) Een groep series bevat enkele serieneigenschappen die gemeenschappelijk zijn voor 
            elke serie in de groep ("series group properties").
            "Series group properties" in ChartSeriesGroup klasse is lezen/schrijven.
            Elke van "series group properties" kan een alleen-lezen projectie hebben in ChartSeries klasse.

### Definitie:
```python
@property
def series_groups(self):
    ...
```

### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* klasse [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)