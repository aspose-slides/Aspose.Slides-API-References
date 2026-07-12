---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Aufzählung von Gruppen kombinierbarer Serienarten.
type: docs
url: /de/com.aspose.slides/combinableseriestypesgroup/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Aufzählung von Gruppen kombinierbarer Serienarten. Jedes Element bezieht sich auf eine Gruppe von Typen von Diagrammserien, die gleichzeitig in einem ChartSeriesGroup auftreten können. Zum Beispiel: ChartType.PercentsStackedArea-Serien können nicht gleichzeitig mit ChartType.StackedArea-Serien in einem ChartSeriesGroup vorkommen. Aber zwei oder mehr ChartType.PercentsStackedArea-Serien können gleichzeitig in einem ChartSeriesGroup vorkommen (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Und ChartType.Line-Serien können gleichzeitig mit ChartType.LineWithMarkers-Serien in einem CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup vorkommen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Gruppiert diese Menge von Serienarten: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Gruppiert diese Menge von Serienarten: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Gruppiert diese Menge von Serienarten: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Gruppiert diese Menge von Serienarten: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Gruppiert diese Menge von Serienarten: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Gruppiert diese Menge von Serienarten: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Gruppiert diese Menge von Serienarten: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Gruppiert diese Menge von Serienarten: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Gruppiert diese Menge von Serienarten: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Gruppiert diese Menge von Serienarten: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Gruppiert diese Menge von Serienarten: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Gruppiert diese Menge von Serienarten: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Gruppiert diese Menge von Serienarten: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Gruppiert diese Menge von Serienarten: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Gruppiert diese Menge von Serienarten: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Gruppiert diese Menge von Serienarten: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Gruppiert diese Menge von Serienarten: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Gruppiert diese Menge von Serienarten: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Gruppiert diese Menge von Serienarten: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Gruppiert diese Menge von Serienarten: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Gruppiert diese Menge von Serienarten: \{ ChartType.Sunburst \}