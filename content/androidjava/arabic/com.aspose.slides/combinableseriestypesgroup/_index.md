---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: تعداد مجموعات أنواع السلاسل القابلة للجمع.
type: docs
url: /ar/com.aspose.slides/combinableseriestypesgroup/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

تعداد مجموعات أنواع السلاسل القابلة للجمع. كل عنصر يرتبط بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في آنٍ واحد داخل ChartSeriesGroup واحد. على سبيل المثال: لا يمكن أن تكون سلسلة ChartType.PercentsStackedArea في آنٍ واحد مع سلسلة ChartType.StackedArea داخل ChartSeriesGroup واحد. ولكن يمكن أن تكون سلسلتان أو أكثر من ChartType.PercentsStackedArea في ChartSeriesGroup واحد في آنٍ واحد (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن أن تكون سلسلة ChartType.Line مع سلسلة ChartType.LineWithMarkers في آنٍ واحد داخل CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

تجمع هذه المجموعة من أنواع السلاسل: \{ ChartType.Sunburst \}