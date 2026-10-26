---
title: CombinableSeriesTypesGroup
second_title: Referência da API Aspose.Sildes para .NET
description: Enumeração de grupos de tipos de séries combináveis. Cada elemento está relacionado a um grupo de tipos de séries de gráfico que podem persistir simultaneamente em um ChartSeriesGroup. Por exemplo, séries ChartType.PercentsStackedArea não podem estar simultaneamente com séries ChartType.StackedArea em um ChartSeriesGroup. Mas duas ou mais séries ChartType.PercentsStackedArea podem estar em um ChartSeriesGroup simultaneamente CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. E séries ChartType.Line podem estar com séries ChartType.LineWithMarkers simultaneamente em um ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.
type: docs
weight: 1530
url: /pt/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Enumeração de grupos de tipos de séries combináveis. Cada elemento se refere a um grupo de tipos de séries de gráfico que podem coexistir simultaneamente em um ChartSeriesGroup. Por exemplo: séries ChartType.PercentsStackedArea não podem estar simultaneamente com séries ChartType.StackedArea em um ChartSeriesGroup. Mas duas ou mais séries ChartType.PercentsStackedArea podem estar em um ChartSeriesGroup simultaneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). E series ChartType.Line podem estar com series ChartType.LineWithMarkers simultaneamente em um ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.

```csharp
public enum CombinableSeriesTypesGroup
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| AreaChart_Area | `4` | Agrupa este conjunto de tipos de séries: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Agrupa este conjunto de tipos de séries: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Agrupa este conjunto de tipos de séries: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Agrupa este conjunto de tipos de séries: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Agrupa este conjunto de tipos de séries: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Agrupa este conjunto de tipos de séries: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Agrupa este conjunto de tipos de séries: { ChartType.Line3D } |
| StockHighLowClose | `18` | Agrupa este conjunto de tipos de séries: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Agrupa este conjunto de tipos de séries: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Agrupa este conjunto de tipos de séries: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Agrupa este conjunto de tipos de séries: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Agrupa este conjunto de tipos de séries: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Agrupa este conjunto de tipos de séries: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Agrupa este conjunto de tipos de séries: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Agrupa este conjunto de tipos de séries: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Agrupa este conjunto de tipos de séries: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Agrupa este conjunto de tipos de séries: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Agrupa este conjunto de tipos de séries: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Agrupa este conjunto de tipos de séries: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Agrupa este conjunto de tipos de séries: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Agrupa este conjunto de tipos de séries: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Agrupa este conjunto de tipos de séries: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Agrupa este conjunto de tipos de séries: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Agrupa este conjunto de tipos de séries: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Agrupa este conjunto de tipos de séries: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Agrupa este conjunto de tipos de séries: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Agrupa este conjunto de tipos de séries: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Agrupa este conjunto de tipos de séries: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Agrupa este conjunto de tipos de séries: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Agrupa este conjunto de tipos de séries: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Agrupa este conjunto de tipos de séries: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Agrupa este conjunto de tipos de séries: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Agrupa este conjunto de tipos de séries: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Agrupa este conjunto de tipos de séries: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Agrupa este conjunto de tipos de séries: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Agrupa este conjunto de tipos de séries: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Agrupa este conjunto de tipos de séries: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Agrupa este conjunto de tipos de séries: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Agrupa este conjunto de tipos de séries: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Agrupa este conjunto de tipos de séries: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Agrupa este conjunto de tipos de séries: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Agrupa este conjunto de tipos de séries: { ChartType.Histogram } |
| ParetoLineChart | `54` | Agrupa este conjunto de tipos de séries: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Agrupa este conjunto de tipos de séries: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Agrupa este conjunto de tipos de séries: { ChartType.Waterfall } |
| FunnelChart | `57` | Agrupa este conjunto de tipos de séries: { ChartType.Funnel } |
| TreemapChart | `58` | Agrupa este conjunto de tipos de séries: { ChartType.Treemap } |
| MapChart | `59` | Agrupa este conjunto de tipos de séries: { ChartType.Map } |
| SunburstChart | `60` | Agrupa este conjunto de tipos de séries: { ChartType.Sunburst } |

### Veja Também

* espaço de nomes [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->