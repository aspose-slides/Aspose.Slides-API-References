---
title: get_SeriesGroups()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les groupes de séries. Lecture seule IChartSeriesGroupCollection.
type: docs
weight: 27
url: /fr/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() méthode

Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées sur les axes primaires ou sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe du regroupement des séries est un groupement par les groupes de types mentionnés ci-dessus et par le type de tracé primaire/secondaire.

2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (\"propriétés du groupe de séries\"). \"propriétés du groupe de séries\" dans la classe [ChartSeriesGroup](../../chartseriesgroup/) sont lecture/écriture. Chacune des \"propriétés du groupe de séries\" peut avoir une projection lecture seule dans la classe [ChartSeries](../../chartseries/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [IChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)