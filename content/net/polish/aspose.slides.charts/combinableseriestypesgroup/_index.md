---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes dla .NET - odniesienie API
description: Enumeracja grup kombinowalnych typów serii. Każdy element odnosi się do grupy typów serii wykresu, które mogą współistnieć jednocześnie w jednej ChartSeriesGroup. Na przykład serie ChartType.PercentsStackedArea nie mogą jednocześnie występować z seriami ChartType.StackedArea w jednej ChartSeriesGroup. Jednak dwie lub więcej serii ChartType.PercentsStackedArea mogą znajdować się w jednej ChartSeriesGroup jednocześnie CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. I serie ChartType.Line mogą być jednocześnie z seriami ChartType.LineWithMarkers w jednej CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /pl/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeracja

Enumeracja grup kombinowalnych typów serii. Każdy element odnosi się do grupy typów serii wykresu, które mogą współistnieć jednocześnie w jednej ChartSeriesGroup. Na przykład serie ChartType.PercentsStackedArea nie mogą jednocześnie występować z serią ChartType.StackedArea w jednej ChartSeriesGroup. Natomiast dwie lub więcej serii ChartType.PercentsStackedArea mogą znajdować się w jednej ChartSeriesGroup jednocześnie (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Seria ChartType.Line może być jednocześnie z serią ChartType.LineWithMarkers w jednej CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| AreaChart_Area | `4` | Grupuje ten zestaw typów serii: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Grupuje ten zestaw typów serii: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Grupuje ten zestaw typów serii: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Grupuje ten zestaw typów serii: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Grupuje ten zestaw typów serii: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Grupuje ten zestaw typów serii: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Grupuje ten zestaw typów serii: { ChartType.Line3D } |
| StockHighLowClose | `18` | Grupuje ten zestaw typów serii: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Grupuje ten zestaw typów serii: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Grupuje ten zestaw typów serii: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Grupuje ten zestaw typów serii: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Grupuje ten zestaw typów serii: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Grupuje ten zestaw typów serii: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Grupuje ten zestaw typów serii: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Grupuje ten zestaw typów serii: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Grupuje ten zestaw typów serii: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Grupuje ten zestaw typów serii: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Grupuje ten zestaw typów serii: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Grupuje ten zestaw typów serii: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Grupuje ten zestaw typów serii: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Grupuje ten zestaw typów serii: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Grupuje ten zestaw typów serii: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Grupuje ten zestaw typów serii: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Grupuje ten zestaw typów serii: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Grupuje ten zestaw typów serii: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Grupuje ten zestaw typów serii: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Grupuje ten zestaw typów serii: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Grupuje ten zestaw typów serii: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Grupuje ten zestaw typów serii: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Grupuje ten zestaw typów serii: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Grupuje ten zestaw typów serii: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Grupuje ten zestaw typów serii: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Grupuje ten zestaw typów serii: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Grupuje ten zestaw typów serii: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Grupuje ten zestaw typów serii: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Grupuje ten zestaw typów serii: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Grupuje ten zestaw typów serii: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Grupuje ten zestaw typów serii: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Grupuje ten zestaw typów serii: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Grupuje ten zestaw typów serii: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Grupuje ten zestaw typów serii: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Grupuje ten zestaw typów serii: { ChartType.Histogram } |
| ParetoLineChart | `54` | Grupuje ten zestaw typów serii: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Grupuje ten zestaw typów serii: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Grupuje ten zestaw typów serii: { ChartType.Waterfall } |
| FunnelChart | `57` | Grupuje ten zestaw typów serii: { ChartType.Funnel } |
| TreemapChart | `58` | Grupuje ten zestaw typów serii: { ChartType.Treemap } |
| MapChart | `59` | Grupuje ten zestaw typów serii: { ChartType.Map } |
| SunburstChart | `60` | Grupuje ten zestaw typów serii: { ChartType.Sunburst } |

### Zobacz także

* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->