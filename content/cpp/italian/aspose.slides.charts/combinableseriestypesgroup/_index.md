---
title: CombinableSeriesTypesGroup
second_title: Riferimento API di Aspose.Slides per C++
description: "Enumerazione dei gruppi di tipi di serie combinabili. Ogni elemento è relativo a un gruppo di tipi di serie di grafico che possono persistere simultaneamente in un ChartSeriesGroup. Per esempio: le serie ChartType::PercentsStackedArea non possono essere simultaneamente con le serie ChartType::StackedArea in un ChartSeriesGroup. Ma due o più ChartType::PercentsStackedArea possono trovarsi in un ChartSeriesGroup simultaneamente (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). E le serie ChartType::Line possono essere con le serie ChartType::LineWithMarkers simultaneamente in un CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /it/aspose.slides.charts/combinableseriestypesgroup/
---
## Enum CombinableSeriesTypesGroup


Enumerazione dei gruppi di tipi di serie combinabili. Ogni elemento si riferisce a un gruppo di tipi di serie di grafico che possono coesistere simultaneamente in un [ChartSeriesGroup](../chartseriesgroup/). Per esempio: le serie [ChartType::PercentsStackedArea](../charttype/) non possono essere simultaneamente con le serie [ChartType::StackedArea](../charttype/) in un [ChartSeriesGroup](../chartseriesgroup/). Ma due o più [ChartType::PercentsStackedArea](../charttype/) possono essere in un [ChartSeriesGroup](../chartseriesgroup/) simultaneamente ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). E le serie [ChartType::Line](../charttype/) possono essere con le serie [ChartType::LineWithMarkers](../charttype/) simultaneamente in un [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AreaChart_Area | 4 | Raggruppa questo insieme di tipi di serie: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Raggruppa questo insieme di tipi di serie: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Raggruppa questo insieme di tipi di serie: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Raggruppa questo insieme di tipi di serie: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Raggruppa questo insieme di tipi di serie: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Raggruppa questo insieme di tipi di serie: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Raggruppa questo insieme di tipi di serie: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Raggruppa questo insieme di tipi di serie: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Raggruppa questo insieme di tipi di serie: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Raggruppa questo insieme di tipi di serie: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Raggruppa questo insieme di tipi di serie: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Raggruppa questo insieme di tipi di serie: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Raggruppa questo insieme di tipi di serie: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Raggruppa questo insieme di tipi di serie: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Raggruppa questo insieme di tipi di serie: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Raggruppa questo insieme di tipi di serie: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Raggruppa questo insieme di tipi di serie: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Raggruppa questo insieme di tipi di serie: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Raggruppa questo insieme di tipi di serie: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Raggruppa questo insieme di tipi di serie: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Raggruppa questo insieme di tipi di serie: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Raggruppa questo insieme di tipi di serie: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Raggruppa questo insieme di tipi di serie: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Raggruppa questo insieme di tipi di serie: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Raggruppa questo insieme di tipi di serie: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Raggruppa questo insieme di tipi di serie: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Raggruppa questo insieme di tipi di serie: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Raggruppa questo insieme di tipi di serie: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Raggruppa questo insieme di tipi di serie: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Raggruppa questo insieme di tipi di serie: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Raggruppa questo insieme di tipi di serie: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Raggruppa questo insieme di tipi di serie: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Raggruppa questo insieme di tipi di serie: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Raggruppa questo insieme di tipi di serie: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Raggruppa questo insieme di tipi di serie: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Raggruppa questo insieme di tipi di serie: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Raggruppa questo insieme di tipi di serie: { [ChartType::Sunburst](../charttype/) } |

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)