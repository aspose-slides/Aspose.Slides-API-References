---
title: series_groups property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups eigenschap
Haalt de groepen van series op.
            Alleen-lezen [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection).


### Opmerkingen

1) Elke groep van series bevat series met combineerbare typen. Groepen van 
            combineerbare serietypen worden gedefinieerd en beschreven met de CombinableSeriesTypesGroup enum.
            Ook bevat elke groep van series series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep).
            Dus is het principe van seriesgroepering een groepering op basis van bovengenoemde typegroepen en op type van primaire/secundaire plot.
            
            2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties").
            "Series group properties" in de ChartSeriesGroup klasse is lezen/schrijven.
            Elke "series group properties" kan een Alleen-lezen projectie hebben in de ChartSeries klasse.

### Definitie:
```python
@property
def series_groups(self):
    ...
```


### Zie ook
* klasse [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata)
* klasse [`IChartSeriesGroupCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)