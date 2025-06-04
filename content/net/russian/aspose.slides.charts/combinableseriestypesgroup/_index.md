---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes для .NET API Справочник
description: Перечисление групп совместимых типов серий. Каждый элемент относится к группе типов серий диаграмм, которые могут существовать одновременно в одной ChartSeriesGroup. Например, серии ChartType.PercentsStackedArea не могут существовать одновременно с сериями ChartType.StackedArea в одной ChartSeriesGroup. Но две или более серии ChartType.PercentsStackedArea могут находиться в одной ChartSeriesGroup одновременно CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. А серии ChartType.Line могут быть с сериями ChartType.LineWithMarkers одновременно в одной CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1450
url: /ru/aspose.slides.charts/combinableseriestypesgroup/
---

## Перечисление CombinableSeriesTypesGroup

Перечисление групп совместимых типов серий. Каждый элемент относится к группе типов серий диаграмм, которые могут существовать одновременно в одной ChartSeriesGroup. Например: серии ChartType.PercentsStackedArea не могут существовать одновременно с сериями ChartType.StackedArea в одной ChartSeriesGroup. Но две или более серии ChartType.PercentsStackedArea могут находиться в одной ChartSeriesGroup одновременно (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). А серии ChartType.Line могут быть с сериями ChartType.LineWithMarkers одновременно в одной CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Значения

| Название | Значение | Описание |
| --- | --- | --- |
| AreaChart_Area | `4` | Группирует этот набор типов серий: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Группирует этот набор типов серий: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Группирует этот набор типов серий: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Группирует этот набор типов серий: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Группирует этот набор типов серий: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Группирует этот набор типов серий: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Группирует этот набор типов серий: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Группирует этот набор типов серий: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Группирует этот набор типов серий: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Группирует этот набор типов серий: { ChartType.Line3D } |
| StockHighLowClose | `18` | Группирует этот набор типов серий: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Группирует этот набор типов серий: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Группирует этот набор типов серий: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Группирует этот набор типов серий: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Группирует этот набор типов серий: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Группирует этот набор типов серий: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Группирует этот набор типов серий: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Группирует этот набор типов серий: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Группирует этот набор типов серий: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Группирует этот набор типов серий: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Группирует этот набор типов серий: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Группирует этот набор типов серий: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Группирует этот набор типов серий: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Группирует этот набор типов серий: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Группирует этот набор типов серий: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Группирует этот набор типов серий: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Группирует этот набор типов серий: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Группирует этот набор типов серий: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Группирует этот набор типов серий: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Группирует этот набор типов серий: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Группирует этот набор типов серий: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Группирует этот набор типов серий: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Группирует этот набор типов серий: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Группирует этот набор типов серий: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Группирует этот набор типов серий: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Группирует этот набор типов серий: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Группирует этот набор типов серий: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Группирует этот набор типов серий: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Группирует этот набор типов серий: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Группирует этот набор типов серий: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Группирует этот набор типов серий: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Группирует этот набор типов серий: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Группирует этот набор типов серий: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Группирует этот набор типов серий: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Группирует этот набор типов серий: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Группирует этот набор типов серий: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Группирует этот набор типов серий: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Группирует этот набор типов серий: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Группирует этот набор типов серий: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Группирует этот набор типов серий: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Группирует этот набор типов серий: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Группирует этот набор типов серий: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Группирует этот набор типов серий: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Группирует этот набор типов серий: { ChartType.Histogram } |
| ParetoLineChart | `54` | Группирует этот набор типов серий: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Группирует этот набор типов серий: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Группирует этот набор типов серий: { ChartType.Waterfall } |
| FunnelChart | `57` | Группирует этот набор типов серий: { ChartType.Funnel } |
| TreemapChart | `58` | Группирует этот набор типов серий: { ChartType.Treemap } |
| MapChart | `59` | Группирует этот набор типов серий: { ChartType.Map } |
| SunburstChart | `60` | Группирует этот набор типов серий: { ChartType.Sunburst } |

### Также см. 

* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->