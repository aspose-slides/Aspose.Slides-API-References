---
title: get_SeriesGroup()
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 222
url: /fr/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) méthode




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) méthode


Renvoie le groupe de séries à l'index spécifié.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Remarques


1) Chaque groupe de séries contient des séries de types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur les axes primaires, soit sur les axes secondaires (pas les deux cas dans le même groupe). Ainsi, le principe de regroupement des séries repose sur le regroupement par les types mentionnés ci-dessus et par le type de tracé primaire/secondaire. 2) Le groupe de séries contient certaines propriétés de séries communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe [ChartSeriesGroup](../../chartseriesgroup/) sont en lecture/écriture. Chacune de ces « propriétés du groupe de séries » peut avoir une projection en lecture-seule dans la classe [ChartSeries](../../chartseries/). 
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)