---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: संयोज्य श्रृंखला प्रकारों के समूहों की गणना।
type: docs
url: /hi/com.aspose.slides/combinableseriestypesgroup/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

संयोज्य श्रृंखला प्रकारों के समूहों की गणना। प्रत्येक तत्व एक समूह के प्रकारों से संबंधित होता है जो एक ChartSeriesGroup में एक साथ मौजूद रह सकते हैं। उदाहरण के लिए: ChartType.PercentsStackedArea श्रृंखला ChartType.StackedArea श्रृंखला के साथ एक ChartSeriesGroup में एक साथ नहीं रह सकती। लेकिन दो या अधिक ChartType.PercentsStackedArea एक ही ChartSeriesGroup में एक साथ हो सकते हैं (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)। और ChartType.Line श्रृंखला ChartType.LineWithMarkers श्रृंखला के साथ एक CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup में एक साथ रह सकती है।

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area } |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea } |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea } |
| [AreaChart_Area3D](#AreaChart-Area3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area3D } |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea3D } |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea3D } |
| [LineChart_Line](#LineChart-Line) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line, ChartType.LineWithMarkers } |
| [LineChart_StackedLine](#LineChart-StackedLine) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| [Line3DChart](#Line3DChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line3D } |
| [StockHighLowClose](#StockHighLowClose) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.HighLowClose } |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.OpenHighLowClose } |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeHighLowClose } |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeOpenHighLowClose } |
| [RadarChart](#RadarChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Radar, ChartType.RadarWithMarkers } |
| [FilledRadarChart](#FilledRadarChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.FilledRadar } |
| [ScatterStraightMarker](#ScatterStraightMarker) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| [PieChart](#PieChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie, ChartType.ExplodedPie } |
| [Pie3DChart](#Pie3DChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| [DoughnutChart](#DoughnutChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| [BarChart_VertClustered](#BarChart-VertClustered) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn } |
| [BarChart_VertStacked](#BarChart-VertStacked) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn } |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn } |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar } |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar } |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar } |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn3D } |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCone } |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCylinder } |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedPyramid } |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn3D } |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCone } |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCylinder } |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedPyramid } |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar3D } |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCone } |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCylinder } |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalPyramid } |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar3D } |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCone } |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCylinder } |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalPyramid } |
| [BarOfPieChart](#BarOfPieChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BarOfPie } |
| [PieOfPieChart](#PieOfPieChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PieOfPie } |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Contour } |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeContour } |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Surface3D } |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeSurface3D } |
| [BubbleChart](#BubbleChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Bubble, ChartType.BubbleWith3D } |
| [HistogramChart](#HistogramChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Histogram } |
| [ParetoLineChart](#ParetoLineChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ParetoLine } |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BoxAndWhisker } |
| [WaterfallChart](#WaterfallChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Waterfall } |
| [FunnelChart](#FunnelChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Funnel } |
| [TreemapChart](#TreemapChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Treemap } |
| [MapChart](#MapChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Map } |
| [SunburstChart](#SunburstChart) | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Sunburst } |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area }

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea }

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea }

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area3D }

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea3D }

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea3D }

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line, ChartType.LineWithMarkers }

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedLine, ChartType.StackedLineWithMarkers }

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers }

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line3D }

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.HighLowClose }

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.OpenHighLowClose }

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeHighLowClose }

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeOpenHighLowClose }

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Radar, ChartType.RadarWithMarkers }

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.FilledRadar }

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers }

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers }

### PieChart {#PieChart}
```
public static final int PieChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie, ChartType.ExplodedPie }

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie3D, ChartType.ExplodedPie3D }

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Doughnut, ChartType.ExplodedDoughnut }

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn }

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn }

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn }

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar }

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar }

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar }

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D }

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid }

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn3D }

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCone }

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCylinder }

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedPyramid }

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn3D }

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCone }

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCylinder }

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedPyramid }

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid }

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar3D }

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCone }

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCylinder }

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalPyramid }

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar3D }

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCone }

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCylinder }

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalPyramid }

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BarOfPie }

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PieOfPie }

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Contour }

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeContour }

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Surface3D }

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeSurface3D }

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Bubble, ChartType.BubbleWith3D }

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Histogram }

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ParetoLine }

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BoxAndWhisker }

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Waterfall }

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Funnel }

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Treemap }

### MapChart {#MapChart}
```
public static final int MapChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Map }

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Sunburst }