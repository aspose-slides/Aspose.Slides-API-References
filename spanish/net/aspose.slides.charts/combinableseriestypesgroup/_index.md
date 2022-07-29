---
title: CombinableSeriesTypesGroup
second_title: Referencia de la API de Aspose.Slides para .NET
description: Enumeración de grupos de tipos de series combinables. Cada elemento se relaciona con un grupo de tipos de series de gráficos que pueden persistir simultáneamente en un ChartSeriesGroup. Por ejemplo la serie ChartType.PercentsStackedArea no puede estar simultáneamente con la serie ChartType.StackedArea en un ChartSeriesGroup. Pero dos o más ChartType.PercentsStackedArea pueden estar en un ChartSeriesGroup simultáneamente CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Y la serie ChartType.Line puede ser con la serie ChartType.LineWithMarkers simultáneamente en un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1390
url: /es/net/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Enumeración de grupos de tipos de series combinables. Cada elemento se relaciona con un grupo de tipos de series de gráficos que pueden persistir simultáneamente en un ChartSeriesGroup. Por ejemplo: la serie ChartType.PercentsStackedArea no puede estar simultáneamente con la serie ChartType.StackedArea en un ChartSeriesGroup. Pero dos o más ChartType.PercentsStackedArea pueden estar en un ChartSeriesGroup simultáneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Y la serie ChartType.Line puede ser con la serie ChartType.LineWithMarkers simultáneamente en un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AreaChart_Area | `4` | Agrupa este conjunto de tipos de series: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Agrupa este conjunto de tipos de series: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Agrupa este conjunto de tipos de series: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Agrupa este conjunto de tipos de series: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Agrupa este conjunto de tipos de series: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Agrupa este conjunto de tipos de series: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Agrupa este conjunto de tipos de series: { ChartType.Line3D } |
| StockHighLowClose | `18` | Agrupa este conjunto de tipos de serie: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Agrupa este conjunto de tipos de serie: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Agrupa este conjunto de tipos de series: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Agrupa este conjunto de tipos de serie: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Agrupa este conjunto de tipos de serie: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Agrupa este conjunto de tipos de series: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Agrupa este conjunto de tipos de series: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Agrupa este conjunto de tipos de series: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Agrupa este conjunto de tipos de serie: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Agrupa este conjunto de tipos de serie: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Agrupa este conjunto de tipos de serie: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Agrupa este conjunto de tipos de series: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Agrupa este conjunto de tipos de series: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Agrupa este conjunto de tipos de series: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Agrupa este conjunto de tipos de series: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Agrupa este conjunto de tipos de series: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Agrupa este conjunto de tipos de series: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Agrupa este conjunto de tipos de series: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Agrupa este conjunto de tipos de serie: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Agrupa este conjunto de tipos de series: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Agrupa este conjunto de tipos de series: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Agrupa este conjunto de tipos de series: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Agrupa este conjunto de tipos de series: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Agrupa este conjunto de tipos de series: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Agrupa este conjunto de tipos de series: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Agrupa este conjunto de tipos de series: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Agrupa este conjunto de tipos de series: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Agrupa este conjunto de tipos de serie: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Agrupa este conjunto de tipos de serie: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Agrupa este conjunto de tipos de series: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Agrupa este conjunto de tipos de series: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Agrupa este conjunto de tipos de series: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Agrupa este conjunto de tipos de series: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Agrupa este conjunto de tipos de series: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Agrupa este conjunto de tipos de series: { ChartType.Histogram } |
| ParetoLineChart | `54` | Agrupa este conjunto de tipos de series: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Agrupa este conjunto de tipos de serie: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Agrupa este conjunto de tipos de series: { ChartType.Waterfall } |
| FunnelChart | `57` | Agrupa este conjunto de tipos de series: { ChartType.Funnel } |
| TreemapChart | `58` | Agrupa este conjunto de tipos de serie: { ChartType.Treemap } |
| MapChart | `59` | Agrupa este conjunto de tipos de series: { ChartType.Map } |
| SunburstChart | `60` | Agrupa este conjunto de tipos de series: { ChartType.Sunburst } |

### Ver también

* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
