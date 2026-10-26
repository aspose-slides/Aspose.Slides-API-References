---
title: CombinableSeriesTypesGroup
second_title: Référence de l'API Java via Aspose.Slides pour Android
description: Énumération des groupes de types de séries combinables.
type: docs
url: /fr/com.aspose.slides/combinableseriestypesgroup/
---
**Héritage:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Énumération des groupes de types de séries combinables. Chaque élément correspond à un groupe de types de séries de diagramme qui peut coexister simultanément dans un ChartSeriesGroup. Par exemple : la série ChartType.PercentsStackedArea ne peut pas être simultanée avec la série ChartType.StackedArea dans un ChartSeriesGroup. Mais deux ou plusieurs séries ChartType.PercentsStackedArea peuvent être dans un même ChartSeriesGroup simultanément (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Et les séries ChartType.Line peuvent être avec les séries ChartType.LineWithMarkers simultanément dans un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## Champs

| Champ | Description |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Regroupe cet ensemble de types de séries : \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Regroupe cet ensemble de types de séries : \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Regroupe cet ensemble de types de séries : \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Regroupe cet ensemble de types de séries : \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Regroupe cet ensemble de types de séries : \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Regroupe cet ensemble de types de séries : \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Regroupe cet ensemble de types de séries : \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Regroupe cet ensemble de types de séries : \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Regroupe cet ensemble de types de séries : \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Regroupe cet ensemble de types de séries : \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Regroupe cet ensemble de types de séries : \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Regroupe cet ensemble de types de séries : \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Regroupe cet ensemble de types de séries : \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Regroupe cet ensemble de types de séries : \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Regroupe cet ensemble de types de séries : \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Regroupe cet ensemble de types de séries : \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Regroupe cet ensemble de types de séries : \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Regroupe cet ensemble de types de séries : \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Regroupe cet ensemble de types de séries : \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Regroupe cet ensemble de types de séries : \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Regroupe cet ensemble de types de séries : \{ ChartType.Area \}
### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedArea \}
### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedArea \}
### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.Area3D \}
### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedArea3D \}
### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedArea3D \}
### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Regroupe cet ensemble de types de séries : \{ ChartType.Line, ChartType.LineWithMarkers \}
### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}
### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}
### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Line3D \}
### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Regroupe cet ensemble de types de séries : \{ ChartType.HighLowClose \}
### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Regroupe cet ensemble de types de séries : \{ ChartType.OpenHighLowClose \}
### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Regroupe cet ensemble de types de séries : \{ ChartType.VolumeHighLowClose \}
### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Regroupe cet ensemble de types de séries : \{ ChartType.VolumeOpenHighLowClose \}
### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Radar, ChartType.RadarWithMarkers \}
### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.FilledRadar \}
### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Regroupe cet ensemble de types de séries : \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}
### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Regroupe cet ensemble de types de séries : \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}
### PieChart {#PieChart}
```
public static final int PieChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Pie, ChartType.ExplodedPie \}
### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}
### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}
### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredColumn \}
### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedColumn \}
### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedColumn \}
### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredBar \}
### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedBar \}
### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedBar \}
### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Regroupe cet ensemble de types de séries : \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}
### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}
### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedColumn3D \}
### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedCone \}
### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedCylinder \}
### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedPyramid \}
### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedColumn3D \}
### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedCone \}
### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedCylinder \}
### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedPyramid \}
### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Regroupe cet ensemble de types de séries : \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}
### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedBar3D \}
### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalCone \}
### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalCylinder \}
### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Regroupe cet ensemble de types de séries : \{ ChartType.StackedHorizontalPyramid \}
### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedBar3D \}
### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalCone \}
### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalCylinder \}
### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Regroupe cet ensemble de types de séries : \{ ChartType.PercentsStackedHorizontalPyramid \}
### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.BarOfPie \}
### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.PieOfPie \}
### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Regroupe cet ensemble de types de séries : \{ ChartType.Contour \}
### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Regroupe cet ensemble de types de séries : \{ ChartType.WireframeContour \}
### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.Surface3D \}
### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Regroupe cet ensemble de types de séries : \{ ChartType.WireframeSurface3D \}
### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Bubble, ChartType.BubbleWith3D \}
### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Histogram \}
### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.ParetoLine \}
### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.BoxAndWhisker \}
### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Waterfall \}
### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Funnel \}
### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Treemap \}
### MapChart {#MapChart}
```
public static final int MapChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Map \}
### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Regroupe cet ensemble de types de séries : \{ ChartType.Sunburst \}