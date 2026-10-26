---
title: series_groups property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups propriété
Obtient les groupes de séries.
            Lecture seule [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection).

### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Groups of 
            combinable series types defined and described with CombinableSeriesTypesGroup 
            enum.
            Also each group of series contains series witch is plotted whether 
            on primary axes or on secondary axes (not both cases in one group).
            So, principle of series grouping is a grouping by type groups mentioned 
            above and by primary/secondary plotting type.

2) Group of series contains some series properies whitch is common for each series in group ("Series group properties").
            "Series group properties" in classe ChartSeriesGroup is lecture/écriture.
            Each of "Series group properties" can have a lecture seule projection in classe ChartSeries.

### Définition:
```python
@property
def series_groups(self):
    ...
```

### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)