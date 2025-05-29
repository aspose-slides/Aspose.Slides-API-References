---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes для .NET API Reference
description: Перечисление групп комбинируемых типов серий. Каждый элемент относится к группе типов серий диаграмм, которые могут одновременно существовать в одной ChartSeriesGroup. Например, серии ChartType.PercentsStackedArea не могут одновременно существовать с сериями ChartType.StackedArea в одной ChartSeriesGroup. Но две или более серии ChartType.PercentsStackedArea могут находиться в одной ChartSeriesGroup одновременно CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. А серии ChartType.Line могут находиться с сериями ChartType.LineWithMarkers одновременно в одной CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1450
url: /ru/aspose.slides.charts/combinableseriestypesgroup/
---

## Перечисление CombinableSeriesTypesGroup

Перечисление групп комбинируемых типов серий. Каждый элемент относится к группе типов серий диаграмм, которые могут одновременно существовать в одной ChartSeriesGroup. Например: серии ChartType.PercentsStackedArea не могут одновременно существовать с сериями ChartType.StackedArea в одной ChartSeriesGroup. Но две или более серии ChartType.PercentsStackedArea могут находиться в одной ChartSeriesGroup одновременно (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). А серии ChartType.Line могут находиться с сериями ChartType.LineWithMarkers одновременно в одной CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Значения

| Название | Значение | Описание |
| --- | --- | --- |
| AreaChart_Area | `4` | Групповая этот набор типов серий: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Групповая этот набор типов серий: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Групповая этот набор типов серий: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Групповая этот набор типов серий: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Групповая этот набор типов серий: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Групповая этот набор типов серий: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Групповая этот набор типов серий: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Групповая этот набор типов серий: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Групповая этот набор типов серий: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Групповая этот набор типов серий: { ChartType.Line3D } |
| StockHighLowClose | `18` | Групповая этот набор типов серий: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Групповая этот набор типов серий: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Групповая этот набор типов серий: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Групповая этот набор типов серий: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Групповая этот набор типов серий: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Групповая этот набор типов серий: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Групповая этот набор типов серий: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Групповая этот набор типов серий: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Групповая этот набор типов серий: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Групповая этот набор типов серий: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Групповая этот набор типов серий: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Групповая этот набор типов серий: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Групповая этот набор типов серий: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Групповая этот набор типов серий: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Групповая этот набор типов серий: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Групповая этот набор типов серий: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Групповая этот набор типов серий: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Групповая этот набор типов серий: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Групповая этот набор типов серий: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Групповая этот набор типов серий: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Групповая этот набор типов серий: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Групповая этот набор типов серий: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Групповая этот набор типов серий: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Групповая этот набор типов серий: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Групповая этот набор типов серий: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Групповая этот набор типов серий: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Групповая этот набор типов серий: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Групповая этот набор типов серий: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Групповая этот набор типов серий: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Групповая этот набор типов серий: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Групповая этот набор типов серий: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Групповая этот набор типов серий: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Групповая этот набор типов серий: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Групповая этот набор типов серий: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Групповая этот набор типов серий: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Групповая этот набор типов серий: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Групповая этот набор типов серий: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Групповая этот набор типов серий: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Групповая этот набор типов серий: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Групповая этот набор типов серий: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Групповая этот набор типов серий: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Групповая этот набор типов серий: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Групповая этот набор типов серий: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Групповая этот набор типов серий: { ChartType.Histogram } |
| ParetoLineChart | `54` | Групповая этот набор типов серий: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Групповая этот набор типов серий: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Групповая этот набор типов серий: { ChartType.Waterfall } |
| FunnelChart | `57` | Групповая этот набор типов серий: { ChartType.Funnel } |
| TreemapChart | `58` | Групповая этот набор типов серий: { ChartType.Treemap } |
| MapChart | `59` | Групповая этот набор типов серий: { ChartType.Map } |
| SunburstChart | `60` | Групповая этот набор типов серий: { ChartType.Sunburst } |

### Смотрите также

* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->