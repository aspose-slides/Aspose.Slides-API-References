---
title: get_SeriesGroup()
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 222
url: /fr/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) méthode




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) méthode


Returns the group of series at the specified index.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Remarks


1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes principaux, soit sur les axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par groupes de types mentionnés ci-dessus et par type de tracé principal/secondaire. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (\"series group properties\"). \"Series group properties\" dans la classe [ChartSeriesGroup](../../chartseriesgroup/) est en lecture/écriture. Chacune des \"series group properties\" peut avoir une projection en lecture seule dans la classe [ChartSeries](../../chartseries/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroup](../../ichartseriesgroup/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)