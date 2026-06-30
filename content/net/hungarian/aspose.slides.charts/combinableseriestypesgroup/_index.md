---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes .NET API referencia
description: Az összevonható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan típuscsoporthoz kapcsolódik, amely a diagram sorozatok típusait jelenti, és egyszerre egy ChartSeriesGroup-ban jelen lehet. Például a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea sorozat lehet egyszerre egy ChartSeriesGroup-ban, például a CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. És a ChartType.Line sorozat lehet egyszerre a ChartType.LineWithMarkers sorozattal egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.
type: docs
weight: 1510
url: /hu/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeráció

A kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan típuscsoporthoz tartozik, amely a diagram sorozatok típusait jelöli, és egyszerre egy ChartSeriesGroup-ban jelen lehet. Például a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea sorozat lehet egyszerre egy ChartSeriesGroup-ban (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). És a ChartType.Line sorozat lehet egyszerre a ChartType.LineWithMarkers sorozattal egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.

```csharp
public enum CombinableSeriesTypesGroup
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| AreaChart_Area | `4` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Line3D } |
| StockHighLowClose | `18` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Histogram } |
| ParetoLineChart | `54` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Waterfall } |
| FunnelChart | `57` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Funnel } |
| TreemapChart | `58` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Treemap } |
| MapChart | `59` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Map } |
| SunburstChart | `60` | Csoportosítja ezt a sorozattípusok készletét: { ChartType.Sunburst } |

### Lásd még

* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->