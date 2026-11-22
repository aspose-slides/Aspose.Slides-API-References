---
title: series_groups property
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups propriété
Obtient les groupes de séries.
Lecture seule [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection).

### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'enum CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un groupement par les groupes de types mentionnés ci-above et par le type de traçage principal/secondaire.

2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chaque « propriété du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

### Définition:
```python
@property
def series_groups(self):
    ...
```

### Voir aussi
* classe [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)