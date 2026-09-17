---
title: series_groups property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups propriété
Obtient les groupes de séries.
            Lecture seule [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection).


### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Groupes de 
            types de séries combinables définis et décrits avec CombinableSeriesTypesGroup enum.
            De plus, chaque groupe de séries contient des séries qui sont tracées soit 
            sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe).
            Ainsi, le principe du regroupement de séries est un regroupement par groupes de types mentionnés 
            ci-dessus et par type de tracé principal/secondaire.
            
2) Un groupe de séries contient certaines propriétés de séries qui sont communes à 
            chaque série du groupe (« propriétés du groupe de séries »).
            « propriétés du groupe de séries » dans la classe ChartSeriesGroup est lecture/écriture.
            Chacune des « propriétés du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

### Définition :
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