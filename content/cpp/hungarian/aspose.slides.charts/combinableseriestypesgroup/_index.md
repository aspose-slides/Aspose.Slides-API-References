---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides C++ API Referencia
description: "Az egymással kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan típuscsoporthoz tartozik, amely egyszerre létezhet egy ChartSeriesGroup-ban. Például: ChartType::PercentsStackedArea sorozat nem lehet egyszerre a ChartType::StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType::PercentsStackedArea sorozat lehet egy ChartSeriesGroup-ban egyszerre (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). És a ChartType::Line sorozat együtt lehet a ChartType::LineWithMarkers sorozattal egy CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup-ban."
type: docs
weight: 1496
url: /hu/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Az egymással kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan csoportot jelöl, amely tartalmazhatja a diagram sorozatok típusait, és egyszerre egy [ChartSeriesGroup](../chartseriesgroup/)-ban létezhet. Például: [ChartType::PercentsStackedArea](../charttype/) sorozat nem lehet egyszerre a [ChartType::StackedArea](../charttype/) sorozattal egy [ChartSeriesGroup](../chartseriesgroup/)-ban. De két vagy több [ChartType::PercentsStackedArea](../charttype/) lehet egy [ChartSeriesGroup](../chartseriesgroup/)-ban egyszerre ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). És a [ChartType::Line](../charttype/) sorozat együtt lehet a [ChartType::LineWithMarkers](../charttype/) sorozattal egy [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/)-ban.

```cpp
enum class CombinableSeriesTypesGroup
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| AreaChart_Area | 4 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Csoportosítja ezt a sorozattípus-készletet: { [ChartType::Sunburst](../charttype/) } |

## Lásd még

* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)