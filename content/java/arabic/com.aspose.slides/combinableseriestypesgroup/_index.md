---
title: CombinableSeriesTypesGroup
second_title: مرجع API لـ Aspose.Slides للـ Java
description: تعداد مجموعات أنواع السلاسل القابلة للدمج.
type: docs
url: /ar/com.aspose.slides/combinableseriestypesgroup/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

تعداد لمجموعات أنواع السلاسل القابلة للدمج. كل عنصر يرتبط بمجموعة من أنواع سلاسل المخطط التي يمكن أن توجد في آن واحد داخل ChartSeriesGroup واحد. على سبيل المثال: لا يمكن أن تكون سلسلة ChartType.PercentsStackedArea متزامنة مع سلسلة ChartType.StackedArea في ChartSeriesGroup واحد. ولكن يمكن أن تكون سلسلتان أو أكثر من ChartType.PercentsStackedArea في ChartSeriesGroup واحد في آن واحد (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن أن تكون سلسلة ChartType.Line مع سلسلة ChartType.LineWithMarkers في نفس ChartSeriesGroup داخل CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## الحقول

| Field | Description |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

تجميع لهذا المجموعة من أنواع السلاسل: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

تجميع هذا المجموعة من أنواع السلاسل: \{ ChartType.Sunburst \}