---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides pro Java API Reference
description: Výčet skupin kombinovatelných typů řad.
type: docs
url: /cs/com.aspose.slides/combinableseriestypesgroup/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Výčet skupin kombinovatelných typů řad. Každý prvek se vztahuje ke skupině typů řad grafu, které mohou existovat současně v jednom ChartSeriesGroup. Například: ChartType.PercentsStackedArea řada nemůže být současně s ChartType.StackedArea řadou v jednom ChartSeriesGroup. Ale dvě nebo více ChartType.PercentsStackedArea mohou být v jednom ChartSeriesGroup současně (CombinableSeriesTypesGroup.AreaChart\_PercentsStackedArea). A ChartType.Line řada může být s ChartType.LineWithMarkers řadou současně v jednom CombinableSeriesTypesGroup.LineChart\_Line ChartSeriesGroup.
## Pole

| Pole | Popis |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Skupiny tohoto souboru typů řad: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Skupiny tohoto souboru typů řad: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Skupiny tohoto souboru typů řad: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Skupiny tohoto souboru typů řad: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Skupiny tohoto souboru typů řad: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Skupiny tohoto souboru typů řad: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Skupiny tohoto souboru typů řad: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Skupiny tohoto souboru typů řad: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Skupiny tohoto souboru typů řad: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Skupiny tohoto souboru typů řad: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Skupiny tohoto souboru typů řad: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Skupiny tohoto souboru typů řad: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Skupiny tohoto souboru typů řad: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Skupiny tohoto souboru typů řad: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Skupiny tohoto souboru typů řad: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Skupiny tohoto souboru typů řad: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Skupiny tohoto souboru typů řad: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Skupiny tohoto souboru typů řad: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Skupiny tohoto souboru typů řad: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Skupiny tohoto souboru typů řad: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Skupiny tohoto souboru typů řad: \{ ChartType.Area \}
### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedArea \}
### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedArea \}
### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.Area3D \}
### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedArea3D \}
### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedArea3D \}
### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Skupiny tohoto souboru typů řad: \{ ChartType.Line, ChartType.LineWithMarkers \}
### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}
### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}
### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Line3D \}
### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Skupiny tohoto souboru typů řad: \{ ChartType.HighLowClose \}
### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Skupiny tohoto souboru typů řad: \{ ChartType.OpenHighLowClose \}
### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Skupiny tohoto souboru typů řad: \{ ChartType.VolumeHighLowClose \}
### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Skupiny tohoto souboru typů řad: \{ ChartType.VolumeOpenHighLowClose \}
### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Radar, ChartType.RadarWithMarkers \}
### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.FilledRadar \}
### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Skupiny tohoto souboru typů řad: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}
### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Skupiny tohoto souboru typů řad: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}
### PieChart {#PieChart}
```
public static final int PieChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Pie, ChartType.ExplodedPie \}
### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}
### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}
### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredColumn \}
### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedColumn \}
### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedColumn \}
### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredBar \}
### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedBar \}
### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedBar \}
### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Skupiny tohoto souboru typů řad: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}
### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}
### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedColumn3D \}
### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedCone \}
### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedCylinder \}
### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedPyramid \}
### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedColumn3D \}
### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedCone \}
### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedCylinder \}
### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedPyramid \}
### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Skupiny tohoto souboru typů řad: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}
### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedBar3D \}
### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalCone \}
### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalCylinder \}
### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Skupiny tohoto souboru typů řad: \{ ChartType.StackedHorizontalPyramid \}
### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedBar3D \}
### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalCone \}
### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalCylinder \}
### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Skupiny tohoto souboru typů řad: \{ ChartType.PercentsStackedHorizontalPyramid \}
### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.BarOfPie \}
### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.PieOfPie \}
### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Skupiny tohoto souboru typů řad: \{ ChartType.Contour \}
### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Skupiny tohoto souboru typů řad: \{ ChartType.WireframeContour \}
### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.Surface3D \}
### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Skupiny tohoto souboru typů řad: \{ ChartType.WireframeSurface3D \}
### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Bubble, ChartType.BubbleWith3D \}
### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Histogram \}
### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.ParetoLine \}
### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.BoxAndWhisker \}
### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Waterfall \}
### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Funnel \}
### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Treemap \}
### MapChart {#MapChart}
```
public static final int MapChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Map \}
### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Skupiny tohoto souboru typů řad: \{ ChartType.Sunburst \}