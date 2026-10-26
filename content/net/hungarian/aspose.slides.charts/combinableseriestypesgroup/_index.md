---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes .NET API hivatkozás
description: A kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan típuscsoporthoz tartozik, amely olyan diagram sorozatok típusait jelöli, amelyek egyszerre megtarthatók egy ChartSeriesGroup-ban. Például a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea szerepelhet egyszerre egy ChartSeriesGroup-ban, például a CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. És a ChartType.Line sorozat együtt lehet a ChartType.LineWithMarkers sorozattal egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.
type: docs
weight: 1530
url: /hu/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeráció

Az összekapcsolható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan típuscsoporthoz tartozik, amely a diagram sorozatok típusait jelöli, és egyszerre létezhet egy ChartSeriesGroup-ban. Például: a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea szerepelhet egyszerre egy ChartSeriesGroup-ban (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). És a ChartType.Line sorozat együtt lehet a ChartType.LineWithMarkers sorozattal egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.

```csharp
public enum CombinableSeriesTypesGroup
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| AreaChart_Area | `4` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Line3D } |
| StockHighLowClose | `18` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Histogram } |
| ParetoLineChart | `54` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Waterfall } |
| FunnelChart | `57` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Funnel } |
| TreemapChart | `58` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Treemap } |
| MapChart | `59` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Map } |
| SunburstChart | `60` | Csoportosítja ezt a sorozattípusok halmazát: { ChartType.Sunburst } |

### Lásd még

* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->