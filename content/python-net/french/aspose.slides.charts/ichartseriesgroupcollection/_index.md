---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection classe

Représente la collection de groupes de séries combinables.

Le type IChartSeriesGroupCollection expose les membres suivants :

Obtient le groupe de séries par index.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un regroupement par les groupes de types mentionnés ci-above et par le type de tracé principal/secondaire.

2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des « propriétés du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)