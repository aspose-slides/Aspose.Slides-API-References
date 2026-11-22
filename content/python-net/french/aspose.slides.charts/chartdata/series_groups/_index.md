---
title: series_groups property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups propriété
Obtient les groupes de séries.
            Lecture seule [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection).

### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. 
            Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. 
            De plus, chaque groupe de séries contient des séries qui sont tracées sur les axes primaires ou sur les axes secondaires (pas les deux cas dans un même groupe). 
            Ainsi, le principe du groupement des séries repose sur un groupement par groupes de types mentionnés ci-dessus et par le type de tracé principal/secondaire.
            
2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe ("Series group properties").
            Les "Series group properties" dans la classe ChartSeriesGroup sont en lecture/écriture. 
            Chaque "series group properties" peut avoir une projection en lecture seule dans la classe ChartSeries.

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