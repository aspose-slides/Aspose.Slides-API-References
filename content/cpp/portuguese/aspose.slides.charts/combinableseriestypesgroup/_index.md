---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides para C++ Referência da API
description: "Enumeração dos grupos de tipos de séries combináveis. Cada elemento relaciona-se a um grupo de tipos de séries de gráfico que podem persistir simultaneamente em um ChartSeriesGroup. Por exemplo: séries ChartType::PercentsStackedArea não podem estar simultaneamente com séries ChartType::StackedArea em um ChartSeriesGroup. Mas duas ou mais ChartType::PercentsStackedArea podem estar em um ChartSeriesGroup simultaneamente (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). E séries ChartType::Line podem estar com séries ChartType::LineWithMarkers simultaneamente em um CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /pt/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Enumeração dos grupos de tipos de séries combináveis. Cada elemento corresponde a um grupo de tipos de séries de gráfico que podem coexistir simultaneamente em um [ChartSeriesGroup](../chartseriesgroup/). Por exemplo: séries [ChartType::PercentsStackedArea](../charttype/) não podem estar simultaneamente com séries [ChartType::StackedArea](../charttype/) em um [ChartSeriesGroup](../chartseriesgroup/). Porém duas ou mais [ChartType::PercentsStackedArea](../charttype/) podem estar em um [ChartSeriesGroup](../chartseriesgroup/) simultaneamente ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). E séries [ChartType::Line](../charttype/) podem estar com séries [ChartType::LineWithMarkers](../charttype/) simultaneamente em um [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Values

| Nome | Valor | Descrição |
| --- | --- | --- |
| AreaChart_Area | 4 | Agrupa este conjunto de tipos de séries: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Agrupa este conjunto de tipos de séries: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Agrupa este conjunto de tipos de séries: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Agrupa este conjunto de tipos de séries: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Agrupa este conjunto de tipos de séries: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Agrupa este conjunto de tipos de séries: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Agrupa este conjunto de tipos de séries: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Agrupa este conjunto de tipos de séries: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Agrupa este conjunto de tipos de séries: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Agrupa este conjunto de tipos de séries: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Agrupa este conjunto de tipos de séries: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Agrupa este conjunto de tipos de séries: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Agrupa este conjunto de tipos de séries: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Agrupa este conjunto de tipos de séries: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Agrupa este conjunto de tipos de séries: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Agrupa este conjunto de tipos de séries: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Agrupa este conjunto de tipos de séries: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Agrupa este conjunto de tipos de séries: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Agrupa este conjunto de tipos de séries: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Agrupa este conjunto de tipos de séries: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Agrupa este conjunto de tipos de séries: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Agrupa este conjunto de tipos de séries: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Agrupa este conjunto de tipos de séries: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Agrupa este conjunto de tipos de séries: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Agrupa este conjunto de tipos de séries: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Agrupa este conjunto de tipos de séries: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Agrupa este conjunto de tipos de séries: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Agrupa este conjunto de tipos de séries: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Agrupa este conjunto de tipos de séries: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Agrupa este conjunto de tipos de séries: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Agrupa este conjunto de tipos de séries: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Agrupa este conjunto de tipos de séries: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Agrupa este conjunto de tipos de séries: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Agrupa este conjunto de tipos de séries: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Agrupa este conjunto de tipos de séries: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Agrupa este conjunto de tipos de séries: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Agrupa este conjunto de tipos de séries: { [ChartType::Sunburst](../charttype/) } |

## Veja Também

* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)