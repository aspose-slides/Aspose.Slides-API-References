---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides voor C++ API-referentie
description: "Opsomming van groepen van combineerbare serietypen. Elk element heeft betrekking op een groep van typen van diagramseries die gelijktijdig kunnen bestaan in één ChartSeriesGroup. Bijvoorbeeld: ChartType::PercentsStackedArea series kunnen niet gelijktijdig met ChartType::StackedArea series in één ChartSeriesGroup. Maar twee of meer ChartType::PercentsStackedArea kunnen gelijktijdig in één ChartSeriesGroup voorkomen (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). En ChartType::Line series kunnen gelijktijdig met ChartType::LineWithMarkers series in één CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /nl/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Opsomming van groepen van combineerbare serietypen. Elk element heeft betrekking op een groep van typen van diagramseries die gelijktijdig kunnen bestaan in één [ChartSeriesGroup](../chartseriesgroup/). Bijvoorbeeld: [ChartType::PercentsStackedArea](../charttype/) series kunnen niet gelijktijdig met [ChartType::StackedArea](../charttype/) series in één [ChartSeriesGroup](../chartseriesgroup/) voorkomen. Maar twee of meer [ChartType::PercentsStackedArea](../charttype/) kunnen gelijktijdig in één [ChartSeriesGroup](../chartseriesgroup/) staan ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). En [ChartType::Line](../charttype/) series kunnen gelijktijdig met [ChartType::LineWithMarkers](../charttype/) series in één [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) staan.

```cpp
enum class CombinableSeriesTypesGroup
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| AreaChart_Area | 4 | Groep van deze set serietypen: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Groep van deze set serietypen: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Groep van deze set serietypen: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Groep van deze set serietypen: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Groep van deze set serietypen: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Groep van deze set serietypen: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Groep van deze set serietypen: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Groep van deze set serietypen: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Groep van deze set serietypen: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Groep van deze set serietypen: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Groep van deze set serietypen: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Groep van deze set serietypen: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Groep van deze set serietypen: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Groep van deze set serietypen: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Groep van deze set serietypen: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Groep van deze set serietypen: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Groep van deze set serietypen: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Groep van deze set serietypen: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Groep van deze set serietypen: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Groep van deze set serietypen: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Groep van deze set serietypen: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Groep van deze set serietypen: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Groep van deze set serietypen: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Groep van deze set serietypen: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Groep van deze set serietypen: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Groep van deze set serietypen: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Groep van deze set serietypen: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Groep van deze set serietypen: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Groep van deze set serietypen: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Groep van deze set serietypen: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Groep van deze set serietypen: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Groep van deze set serietypen: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Groep van deze set serietypen: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Groep van deze set serietypen: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Groep van deze set serietypen: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Groep van deze set serietypen: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Groep van deze set serietypen: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Groep van deze set serietypen: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Groep van deze set serietypen: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Groep van deze set serietypen: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Groep van deze set serietypen: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Groep van deze set serietypen: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Groep van deze set serietypen: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Groep van deze set serietypen: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Groep van deze set serietypen: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Groep van deze set serietypen: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Groep van deze set serietypen: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Groep van deze set serietypen: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Groep van deze set serietypen: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Groep van deze set serietypen: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Groep van deze set serietypen: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Groep van deze set serietypen: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Groep van deze set serietypen: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Groep van deze set serietypen: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Groep van deze set serietypen: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Groep van deze set serietypen: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Groep van deze set serietypen: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Groep van deze set serietypen: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Groep van deze set serietypen: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Groep van deze set serietypen: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Groep van deze set serietypen: { [ChartType::Sunburst](../charttype/) } |

## Zie ook

* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)