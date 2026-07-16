---
title: CombinableSeriesTypesGroup
second_title: Référence API Aspose.Slides pour C++
description: "Énumération des groupes de types de séries combinables. Chaque élément correspond à un groupe de types de séries de graphique qui peuvent persister simultanément dans un ChartSeriesGroup. Par exemple : les séries ChartType::PercentsStackedArea ne peuvent pas être simultanément avec les séries ChartType::StackedArea dans un ChartSeriesGroup. Mais deux ou plus de séries ChartType::PercentsStackedArea peuvent être dans un ChartSeriesGroup simultanément (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Et les séries ChartType::Line peuvent être avec les séries ChartType::LineWithMarkers simultanément dans un CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /fr/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Énumération des groupes de types de séries combinables. Chaque élément correspond à un groupe de types de séries de graphique qui peuvent coexister simultanément dans un [ChartSeriesGroup](../chartseriesgroup/). Par exemple : les séries [ChartType::PercentsStackedArea](../charttype/) ne peuvent pas être simultanément avec les séries [ChartType::StackedArea](../charttype/) dans un [ChartSeriesGroup](../chartseriesgroup/). Mais deux ou plus [ChartType::PercentsStackedArea](../charttype/) peuvent être dans un [ChartSeriesGroup](../chartseriesgroup/) simultanément ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Et les séries [ChartType::Line](../charttype/) peuvent être avec les séries [ChartType::LineWithMarkers](../charttype/) simultanément dans un [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AreaChart_Area | 4 | Regroupe cet ensemble de types de séries : { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Regroupe cet ensemble de types de séries : { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Regroupe cet ensemble de types de séries : { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Regroupe cet ensemble de types de séries : { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Regroupe cet ensemble de types de séries : { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Regroupe cet ensemble de types de séries : { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Regroupe cet ensemble de types de séries : { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Regroupe cet ensemble de types de séries : { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Regroupe cet ensemble de types de séries : { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Regroupe cet ensemble de types de séries : { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Regroupe cet ensemble de types de séries : { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Regroupe cet ensemble de types de séries : { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Regroupe cet ensemble de types de séries : { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Regroupe cet ensemble de types de séries : { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Regroupe cet ensemble de types de séries : { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Regroupe cet ensemble de types de séries : { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Regroupe cet ensemble de types de séries : { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Regroupe cet ensemble de types de séries : { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Regroupe cet ensemble de types de séries : { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Regroupe cet ensemble de types de séries : { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Regroupe cet ensemble de types de séries : { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Regroupe cet ensemble de types de séries : { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Regroupe cet ensemble de types de séries : { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Regroupe cet ensemble de types de séries : { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Regroupe cet ensemble de types de séries : { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Regroupe cet ensemble de types de séries : { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Regroupe cet ensemble de types de séries : { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Regroupe cet ensemble de types de séries : { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Regroupe cet ensemble de types de séries : { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Regroupe cet ensemble de types de séries : { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Regroupe cet ensemble de types de séries : { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Regroupe cet ensemble de types de séries : { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Regroupe cet ensemble de types de séries : { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Regroupe cet ensemble de types de séries : { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Regroupe cet ensemble de types de séries : { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Regroupe cet ensemble de types de séries : { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Regroupe cet ensemble de types de séries : { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Regroupe cet ensemble de types de séries : { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Regroupe cet ensemble de types de séries : { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Regroupe cet ensemble de types de séries : { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Regroupe cet ensemble de types de séries : { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Regroupe cet ensemble de types de séries : { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Regroupe cet ensemble de types de séries : { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Regroupe cet ensemble de types de séries : { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Regroupe cet ensemble de types de séries : { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Regroupe cet ensemble de types de séries : { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Regroupe cet ensemble de types de séries : { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Regroupe cet ensemble de types de séries : { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Regroupe cet ensemble de types de séries : { [ChartType::Sunburst](../charttype/) } |

## Voir aussi

* Espace de noms [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)