---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides per Android tramite Java API Reference
description: Enumerazione dei gruppi di tipi di serie combinabili.
type: docs
url: /it/com.aspose.slides/combinableseriestypesgroup/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Enumerazione dei gruppi di tipi di serie combinabili. Ogni elemento è correlato a un gruppo di tipi di serie di grafico che possono coesistere simultaneamente in un ChartSeriesGroup. Per esempio: le serie ChartType.PercentsStackedArea non possono essere contemporaneamente con le serie ChartType.StackedArea in un ChartSeriesGroup. Ma due o più serie ChartType.PercentsStackedArea possono trovarsi nello stesso ChartSeriesGroup simultaneamente (CombinableSeriesTypesGroup.AreaChart\_PercentsStackedArea). E le serie ChartType.Line possono coesistere con le serie ChartType.LineWithMarkers simultaneamente in un ChartSeriesGroup CombinableSeriesTypesGroup.LineChart\_Line ChartSeriesGroup.
## Campi

| Campo | Descrizione |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Raggruppa questo insieme di tipi di serie: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Raggruppa questo insieme di tipi di serie: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Raggruppa questo insieme di tipi di serie: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Raggruppa questo insieme di tipi di serie: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Raggruppa questo insieme di tipi di serie: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Raggruppa questo insieme di tipi di serie: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Raggruppa questo insieme di tipi di serie: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Area \}
### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedArea \}
### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedArea \}
### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Area3D \}
### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedArea3D \}
### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedArea3D \}
### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Line, ChartType.LineWithMarkers \}
### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}
### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}
### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Line3D \}
### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.HighLowClose \}
### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.OpenHighLowClose \}
### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.VolumeHighLowClose \}
### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.VolumeOpenHighLowClose \}
### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Radar, ChartType.RadarWithMarkers \}
### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.FilledRadar \}
### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}
### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}
### PieChart {#PieChart}
```
public static final int PieChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Pie, ChartType.ExplodedPie \}
### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}
### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}
### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredColumn \}
### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedColumn \}
### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedColumn \}
### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredBar \}
### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedBar \}
### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedBar \}
### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}
### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}
### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedColumn3D \}
### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedCone \}
### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedCylinder \}
### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedPyramid \}
### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedColumn3D \}
### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedCone \}
### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedCylinder \}
### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedPyramid \}
### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}
### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedBar3D \}
### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalCone \}
### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalCylinder \}
### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.StackedHorizontalPyramid \}
### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedBar3D \}
### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalCone \}
### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalCylinder \}
### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PercentsStackedHorizontalPyramid \}
### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.BarOfPie \}
### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.PieOfPie \}
### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Contour \}
### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.WireframeContour \}
### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Surface3D \}
### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.WireframeSurface3D \}
### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Bubble, ChartType.BubbleWith3D \}
### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Histogram \}
### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.ParetoLine \}
### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.BoxAndWhisker \}
### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Waterfall \}
### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Funnel \}
### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Treemap \}
### MapChart {#MapChart}
```
public static final int MapChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Map \}
### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Raggruppa questo insieme di tipi di serie: \{ ChartType.Sunburst \}