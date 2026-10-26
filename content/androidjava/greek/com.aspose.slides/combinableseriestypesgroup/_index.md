---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Απαρίθμηση ομάδων συνδυάσιμων τύπων σειρών.
type: docs
url: /el/com.aspose.slides/combinableseriestypesgroup/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Απαρίθμηση ομάδων συνδυάσιμων τύπων σειράς. Κάθε στοιχείο σχετίζεται με ομάδα τύπων σειράς διαγραμμάτων που μπορούν να υπάρξουν ταυτόχρονα σε ένα ChartSeriesGroup. Για παράδειγμα: οι σειρές ChartType.PercentsStackedArea δεν μπορούν να είναι ταυτόχρονα με τις σειρές ChartType.StackedArea σε ένα ChartSeriesGroup. Αλλά δύο ή περισσότερες σειρές ChartType.PercentsStackedArea μπορούν να βρίσκονται σε ένα ChartSeriesGroup ταυτόχρονα (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Και οι σειρές ChartType.Line μπορούν να είναι μαζί με τις σειρές ChartType.LineWithMarkers ταυτόχρονα σε ένα CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## Πεδία

| Field | Description |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

 Ομάδες αυτού του συνόλου τύπων σειράς: \{ ChartType.Sunburst \}