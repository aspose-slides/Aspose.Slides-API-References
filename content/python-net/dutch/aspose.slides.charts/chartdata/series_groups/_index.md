---
title: series_groups property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups eigenschap
Haalt de groepen van series op.
            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection).


### Opmerkingen

1) Elke groep van series bevat series met combineerbare typen. Groepen van 
            combineerbare serietypen zijn gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup 
            .
            Ook bevat elke groep van series series die worden geplot op primaire assen of op secundaire assen (niet beide gevallen in één groep).
            Dus, het principe van seriegroepering is een groepering op typegroepen zoals hierboven vermeld en op het type plotten (primaire/secundaire).
            
            2) Een groep van series bevat enkele serieregels die gemeenschappelijk zijn voor elke serie in de groep ("series group properties").
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