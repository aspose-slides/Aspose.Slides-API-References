---
title: get_SeriesGroups()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère les groupes de séries. Lecture seule IChartSeriesGroupCollection.
type: docs
weight: 27
url: /fr/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() method

Récupère les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un groupement par les groupes de types mentionnés ci-dessus et par le type de tracé primaire/secondaire.

2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe [ChartSeriesGroup](../../chartseriesgroup/) sont lecture/écriture. Chaque « propriété du groupe de séries » peut avoir une projection lecture seule dans la classe [ChartSeries](../../chartseries/). 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)