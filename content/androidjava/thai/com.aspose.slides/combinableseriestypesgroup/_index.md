---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: การแยกประเภทของกลุ่มประเภทซีรีส์ที่สามารถผสานรวมกันได้.
type: docs
url: /th/com.aspose.slides/combinableseriestypesgroup/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

การจัดกลุ่มของประเภทซีรีส์ที่สามารถผสานรวมกันได้. แต่ละอิลิเมนต์สัมพันธ์กับกลุ่มของประเภทซีรีส์ของแผนภูมิที่สามารถอยู่ร่วมกันได้ในหนึ่ง ChartSeriesGroup. ตัวอย่าง: ซีรีส์ ChartType.PercentsStackedArea ไม่สามารถอยู่ร่วมกับซีรีส์ ChartType.StackedArea ในหนึ่ง ChartSeriesGroup. แต่สองหรือมากกว่า ChartType.PercentsStackedArea สามารถอยู่ในหนึ่ง ChartSeriesGroup พร้อมกัน (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). และซีรีส์ ChartType.Line สามารถอยู่พร้อมกับซีรีส์ ChartType.LineWithMarkers ในหนึ่ง CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Sunburst \} |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

จัดกลุ่มชุดประเภทซีรีส์ต่อไปนี้: \{ ChartType.Sunburst \}