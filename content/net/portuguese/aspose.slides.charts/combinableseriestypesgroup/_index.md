---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes para .NET Referência da API
description: Enumeração de grupos de tipos de séries combináveis. Cada elemento está relacionado a um grupo de tipos de séries de gráfico que podem coexistir simultaneamente em um ChartSeriesGroup. Por exemplo, séries ChartType.PercentsStackedArea não podem estar simultaneamente com séries ChartType.StackedArea em um ChartSeriesGroup. Mas duas ou mais séries ChartType.PercentsStackedArea podem estar em um ChartSeriesGroup simultaneamente CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. E séries ChartType.Line podem estar com séries ChartType.LineWithMarkers simultaneamente em um CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1540
url: /pt/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeração

Enumeração de grupos de tipos de séries combináveis. Cada elemento refere-se a um grupo de tipos de séries de gráfico que podem coexistir simultaneamente em um ChartSeriesGroup. Por exemplo: séries ChartType.PercentsStackedArea não podem estar simultaneamente com séries ChartType.StackedArea em um ChartSeriesGroup. Mas duas ou mais séries ChartType.PercentsStackedArea podem estar em um ChartSeriesGroup ao mesmo tempo (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). E séries ChartType.Line podem estar com séries ChartType.LineWithMarkers simultaneamente em um CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| AreaChart_Area | `4` | Agrupa este conjunto de tipos de série: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Agrupa este conjunto de tipos de série: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Agrupa este conjunto de tipos de série: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Agrupa este conjunto de tipos de série: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Agrupa este conjunto de tipos de série: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Agrupa este conjunto de tipos de série: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Agrupa este conjunto de tipos de série: { ChartType.Line3D } |
| StockHighLowClose | `18` | Agrupa este conjunto de tipos de série: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Agrupa este conjunto de tipos de série: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Agrupa este conjunto de tipos de série: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Agrupa este conjunto de tipos de série: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Agrupa este conjunto de tipos de série: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Agrupa este conjunto de tipos de série: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Agrupa este conjunto de tipos de série: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Agrupa este conjunto de tipos de série: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Agrupa este conjunto de tipos de série: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Agrupa este conjunto de tipos de série: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Agrupa este conjunto de tipos de série: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Agrupa este conjunto de tipos de série: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Agrupa este conjunto de tipos de série: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Agrupa este conjunto de tipos de série: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Agrupa este conjunto de tipos de série: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Agrupa este conjunto de tipos de série: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Agrupa este conjunto de tipos de série: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Agrupa este conjunto de tipos de série: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Agrupa este conjunto de tipos de série: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Agrupa este conjunto de tipos de série: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Agrupa este conjunto de tipos de série: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Agrupa este conjunto de tipos de série: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Agrupa este conjunto de tipos de série: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Agrupa este conjunto de tipos de série: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Agrupa este conjunto de tipos de série: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Agrupa este conjunto de tipos de série: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Agrupa este conjunto de tipos de série: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Agrupa este conjunto de tipos de série: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Agrupa este conjunto de tipos de série: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Agrupa este conjunto de tipos de série: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Agrupa este conjunto de tipos de série: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Agrupa este conjunto de tipos de série: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Agrupa este conjunto de tipos de série: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Agrupa este conjunto de tipos de série: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Agrupa este conjunto de tipos de série: { ChartType.Histogram } |
| ParetoLineChart | `54` | Agrupa este conjunto de tipos de série: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Agrupa este conjunto de tipos de série: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Agrupa este conjunto de tipos de série: { ChartType.Waterfall } |
| FunnelChart | `57` | Agrupa este conjunto de tipos de série: { ChartType.Funnel } |
| TreemapChart | `58` | Agrupa este conjunto de tipos de série: { ChartType.Treemap } |
| MapChart | `59` | Agrupa este conjunto de tipos de série: { ChartType.Map } |
| SunburstChart | `60` | Agrupa este conjunto de tipos de série: { ChartType.Sunburst } |

### Veja Também

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->