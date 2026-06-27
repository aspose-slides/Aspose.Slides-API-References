---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes için .NET API Referansı
description: Birleştirilebilir seri türlerinin gruplarının enum’u. Her öğe, bir ChartSeriesGroup içinde aynı anda var olabilen grafik serisi türleri grubuna ilişkilidir. Örneğin ChartType.PercentsStackedArea serisi bir ChartSeriesGroup içinde ChartType.StackedArea serisiyle aynı anda bulunamaz. Ancak iki veya daha fazla ChartType.PercentsStackedArea bir ChartSeriesGroup içinde aynı anda CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea olarak bulunabilir. Ve ChartType.Line serisi ChartType.LineWithMarkers serisiyle aynı anda bir CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup içinde bulunabilir.
type: docs
weight: 1510
url: /tr/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Birleştirilebilir seri türlerinin gruplarının enum’ı. Her öğe, bir ChartSeriesGroup içinde aynı anda var olabilen grafik serisi türleri grubuna ilişkilidir. Örneğin: ChartType.PercentsStackedArea serisi, bir ChartSeriesGroup içinde ChartType.StackedArea serisiyle aynı anda bulunamaz. Ancak iki veya daha fazla ChartType.PercentsStackedArea bir ChartSeriesGroup içinde aynı anda bulunabilir (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Ve ChartType.Line serisi, ChartType.LineWithMarkers serisiyle aynı anda bir CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup içinde bulunabilir.

```csharp
public enum CombinableSeriesTypesGroup
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AreaChart_Area | `4` | Bu seri türleri kümesini gruplar: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Bu seri türleri kümesini gruplar: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Bu seri türleri kümesini gruplar: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Bu seri türleri kümesini gruplar: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Bu seri türleri kümesini gruplar: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Bu seri türleri kümesini gruplar: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Bu seri türleri kümesini gruplar: { ChartType.Line3D } |
| StockHighLowClose | `18` | Bu seri türleri kümesini gruplar: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Bu seri türleri kümesini gruplar: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Bu seri türleri kümesini gruplar: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Bu seri türleri kümesini gruplar: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Bu seri türleri kümesini gruplar: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Bu seri türleri kümesini gruplar: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Bu seri türleri kümesini gruplar: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Bu seri türleri kümesini gruplar: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Bu seri türleri kümesini gruplar: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Bu seri türleri kümesini gruplar: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Bu seri türleri kümesini gruplar: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Bu seri türleri kümesini gruplar: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Bu seri türleri kümesini gruplar: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Bu seri türleri kümesini gruplar: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Bu seri türleri kümesini gruplar: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Bu seri türleri kümesini gruplar: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Bu seri türleri kümesini gruplar: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Bu seri türleri kümesini gruplar: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Bu seri türleri kümesini gruplar: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Bu seri türleri kümesini gruplar: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Bu seri türleri kümesini gruplar: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Bu seri türleri kümesini gruplar: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Bu seri türleri kümesini gruplar: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Bu seri türleri kümesini gruplar: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Bu seri türleri kümesini gruplar: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Bu seri türleri kümesini gruplar: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Bu seri türleri kümesini gruplar: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Bu seri türleri kümesini gruplar: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Bu seri türleri kümesini gruplar: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Bu seri türleri kümesini gruplar: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Bu seri türleri kümesini gruplar: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Bu seri türleri kümesini gruplar: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Bu seri türleri kümesini gruplar: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Bu seri türleri kümesini gruplar: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Bu seri türleri kümesini gruplar: { ChartType.Histogram } |
| ParetoLineChart | `54` | Bu seri türleri kümesini gruplar: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Bu seri türleri kümesini gruplar: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Bu seri türleri kümesini gruplar: { ChartType.Waterfall } |
| FunnelChart | `57` | Bu seri türleri kümesini gruplar: { ChartType.Funnel } |
| TreemapChart | `58` | Bu seri türleri kümesini gruplar: { ChartType.Treemap } |
| MapChart | `59` | Bu seri türleri kümesini gruplar: { ChartType.Map } |
| SunburstChart | `60` | Bu seri türleri kümesini gruplar: { ChartType.Sunburst } |

### Ayrıca Bakınız

* ad alan [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->