---
title: CombinableSeriesTypesGroup
second_title: Referencia de la API de Aspose.Slides para C++
description: "Enumeración de grupos de tipos de series combinables. Cada elemento se relaciona con un grupo de tipos de series de gráfico que pueden persistir simultáneamente en un ChartSeriesGroup. Por ejemplo: las series ChartType::PercentsStackedArea no pueden estar simultáneamente con las series ChartType::StackedArea en un ChartSeriesGroup. Pero dos o más ChartType::PercentsStackedArea pueden estar en un ChartSeriesGroup simultáneamente (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Y las series ChartType::Line pueden estar con las series ChartType::LineWithMarkers simultáneamente en un CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /es/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeración


Enumeración de grupos de tipos de series combinables. Cada elemento se relaciona con un grupo de tipos de series de gráfico que pueden persistir simultáneamente en un [ChartSeriesGroup](../chartseriesgroup/). Por ejemplo: las series [ChartType::PercentsStackedArea](../charttype/) no pueden estar simultáneamente con las series [ChartType::StackedArea](../charttype/) en un [ChartSeriesGroup](../chartseriesgroup/). Pero dos o más [ChartType::PercentsStackedArea](../charttype/) pueden estar en un [ChartSeriesGroup](../chartseriesgroup/) simultáneamente ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Y las series [ChartType::Line](../charttype/) pueden estar con las series [ChartType::LineWithMarkers](../charttype/) simultáneamente en un [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AreaChart_Area | 4 | Agrupa este conjunto de tipos de series: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Agrupa este conjunto de tipos de series: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Agrupa este conjunto de tipos de series: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Agrupa este conjunto de tipos de series: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Agrupa este conjunto de tipos de series: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Agrupa este conjunto de tipos de series: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Agrupa este conjunto de tipos de series: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Agrupa este conjunto de tipos de series: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Agrupa este conjunto de tipos de series: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Agrupa este conjunto de tipos de series: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Agrupa este conjunto de tipos de series: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Agrupa este conjunto de tipos de series: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Agrupa este conjunto de tipos de series: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Agrupa este conjunto de tipos de series: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Agrupa este conjunto de tipos de series: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Agrupa este conjunto de tipos de series: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Agrupa este conjunto de tipos de series: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Agrupa este conjunto de tipos de series: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Agrupa este conjunto de tipos de series: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Agrupa este conjunto de tipos de series: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Agrupa este conjunto de tipos de series: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Agrupa este conjunto de tipos de series: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Agrupa este conjunto de tipos de series: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Agrupa este conjunto de tipos de series: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Agrupa este conjunto de tipos de series: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Agrupa este conjunto de tipos de series: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Agrupa este conjunto de tipos de series: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Agrupa este conjunto de tipos de series: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Agrupa este conjunto de tipos de series: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Agrupa este conjunto de tipos de series: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Agrupa este conjunto de tipos de series: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Agrupa este conjunto de tipos de series: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Agrupa este conjunto de tipos de series: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Agrupa este conjunto de tipos de series: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Agrupa este conjunto de tipos de series: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Agrupa este conjunto de tipos de series: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Agrupa este conjunto de tipos de series: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Agrupa este conjunto de tipos de series: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Agrupa este conjunto de tipos de series: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Agrupa este conjunto de tipos de series: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Agrupa este conjunto de tipos de series: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Agrupa este conjunto de tipos de series: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Agrupa este conjunto de tipos de series: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Agrupa este conjunto de tipos de series: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Agrupa este conjunto de tipos de series: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Agrupa este conjunto de tipos de series: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Agrupa este conjunto de tipos de series: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Agrupa este conjunto de tipos de series: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Agrupa este conjunto de tipos de series: { [ChartType::Sunburst](../charttype/) } |

## Ver también

* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)