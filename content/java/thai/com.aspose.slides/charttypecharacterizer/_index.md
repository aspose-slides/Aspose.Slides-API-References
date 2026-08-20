---
title: ChartTypeCharacterizer
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ตัวช่วยสำหรับรับข้อมูลเพิ่มเติมเกี่ยวกับแผนภูมิและชุดข้อมูลตาม ChartType ของมัน.
type: docs
url: /th/com.aspose.slides/charttypecharacterizer/
---
**การสืบทอด:**
java.lang.Object
```
public class ChartTypeCharacterizer
```

ตัวช่วยสำหรับรับข้อมูลเพิ่มเติมเกี่ยวกับแผนภูมิและชุดข้อมูลตาม ChartType ของมัน.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ChartTypeCharacterizer()](#ChartTypeCharacterizer--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isBar3DChart(int chartType)](#isBar3DChart-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ bar3DChart (คอลัมน์หรือแถบ 3D). |
| [is2DChart(int chartType)](#is2DChart-int-) | คืนค่า true หาก chartType เป็นหนึ่งในประเภทแผนภูมิ 2D. |
| [is3DChart(int chartType)](#is3DChart-int-) | คืนค่า true หาก chartType เป็นหนึ่งในประเภทแผนภูมิ 3D. |
| [isChartTypeColumn(int chartType)](#isChartTypeColumn-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Column. |
| [isChartTypeLine(int chartType)](#isChartTypeLine-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Line. |
| [isChartTypePie(int chartType)](#isChartTypePie-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Pie. |
| [isChartTypeBar(int chartType)](#isChartTypeBar-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Bar. |
| [isChartTypeArea(int chartType)](#isChartTypeArea-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Area. |
| [isChartTypeScatter(int chartType)](#isChartTypeScatter-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Scatter. |
| [isChartTypeStock(int chartType)](#isChartTypeStock-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Stock. |
| [isChartTypeSurface(int chartType)](#isChartTypeSurface-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Surface. |
| [isChartTypeDoughnut(int chartType)](#isChartTypeDoughnut-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Doughnut. |
| [isChartTypeBubble(int chartType)](#isChartTypeBubble-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Bubble. |
| [isChartTypeRadar(int chartType)](#isChartTypeRadar-int-) | คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Radar. |
| [isSeriesUsesXValueCoordinate(int seriesType)](#isSeriesUsesXValueCoordinate-int-) | คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า X. |
| [isSeriesUsesYValueCoordinate(int seriesType)](#isSeriesUsesYValueCoordinate-int-) | คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า Y. |
| [isSeriesUsesValueCoordinate(int seriesType)](#isSeriesUsesValueCoordinate-int-) | คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า. |
| [isSeriesUsesBubbleSizeCoordinate(int seriesType)](#isSeriesUsesBubbleSizeCoordinate-int-) | คืนค่า true หากพิกัดขนาดบับเบิลสามารถใช้ได้กับ series type ที่ระบุ. |
| [hasSeriesTrendLines(int seriesType)](#hasSeriesTrendLines-int-) | คืนค่า true หากมีเส้นแนวโน้มของ series สำหรับ series type ที่ระบุ. |
| [isErrorBarsXAllowed(int seriesType)](#isErrorBarsXAllowed-int-) | คืนค่า true หากแถบความผิดพลาด X ได้รับอนุญาตสำหรับ series type ที่ระบุ. |
| [isErrorBarsYAllowed(int seriesType)](#isErrorBarsYAllowed-int-) | คืนค่า true หากแถบความผิดพลาด Y ได้รับอนุญาตสำหรับ series type ที่ระบุ. |
### ChartTypeCharacterizer() {#ChartTypeCharacterizer--}
```
public ChartTypeCharacterizer()
```


### isBar3DChart(int chartType) {#isBar3DChart-int-}
```
public static boolean isBar3DChart(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ bar3DChart (คอลัมน์หรือแถบ 3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### is2DChart(int chartType) {#is2DChart-int-}
```
public static boolean is2DChart(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งในประเภทแผนภูมิ 2D.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### is3DChart(int chartType) {#is3DChart-int-}
```
public static boolean is3DChart(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งในประเภทแผนภูมิ 3D.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeColumn(int chartType) {#isChartTypeColumn-int-}
```
public static boolean isChartTypeColumn(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Column. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.ClusteredColumn](../../com.aspose.slides/charttype\#ClusteredColumn), [ChartType.ClusteredColumn3D](../../com.aspose.slides/charttype\#ClusteredColumn3D), [ChartType.ClusteredCone](../../com.aspose.slides/charttype\#ClusteredCone), [ChartType.ClusteredCylinder](../../com.aspose.slides/charttype\#ClusteredCylinder), [ChartType.ClusteredPyramid](../../com.aspose.slides/charttype\#ClusteredPyramid), [ChartType.PercentsStackedColumn](../../com.aspose.slides/charttype\#PercentsStackedColumn), [ChartType.PercentsStackedColumn3D](../../com.aspose.slides/charttype\#PercentsStackedColumn3D), [ChartType.PercentsStackedCone](../../com.aspose.slides/charttype\#PercentsStackedCone), [ChartType.PercentsStackedCylinder](../../com.aspose.slides/charttype\#PercentsStackedCylinder), [ChartType.PercentsStackedPyramid](../../com.aspose.slides/charttype\#PercentsStackedPyramid), [ChartType.StackedColumn](../../com.aspose.slides/charttype\#StackedColumn), [ChartType.StackedColumn3D](../../com.aspose.slides/charttype\#StackedColumn3D), [ChartType.StackedCone](../../com.aspose.slides/charttype\#StackedCone), [ChartType.StackedCylinder](../../com.aspose.slides/charttype\#StackedCylinder), [ChartType.StackedPyramid](../../com.aspose.slides/charttype\#StackedPyramid), [ChartType.Column3D](../../com.aspose.slides/charttype\#Column3D), [ChartType.Cylinder3D](../../com.aspose.slides/charttype\#Cylinder3D), [ChartType.Cone3D](../../com.aspose.slides/charttype\#Cone3D), [ChartType.Pyramid3D](../../com.aspose.slides/charttype\#Pyramid3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeLine(int chartType) {#isChartTypeLine-int-}
```
public static boolean isChartTypeLine(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Line. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.Line](../../com.aspose.slides/charttype\#Line), [ChartType.LineWithMarkers](../../com.aspose.slides/charttype\#LineWithMarkers), [ChartType.PercentsStackedLine](../../com.aspose.slides/charttype\#PercentsStackedLine), [ChartType.PercentsStackedLineWithMarkers](../../com.aspose.slides/charttype\#PercentsStackedLineWithMarkers), [ChartType.StackedLine](../../com.aspose.slides/charttype\#StackedLine), [ChartType.StackedLineWithMarkers](../../com.aspose.slides/charttype\#StackedLineWithMarkers), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypePie(int chartType) {#isChartTypePie-int-}
```
public static boolean isChartTypePie(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Pie. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.ExplodedPie](../../com.aspose.slides/charttype\#ExplodedPie), [ChartType.ExplodedPie3D](../../com.aspose.slides/charttype\#ExplodedPie3D), [ChartType.Pie](../../com.aspose.slides/charttype\#Pie), [ChartType.Pie3D](../../com.aspose.slides/charttype\#Pie3D), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeBar(int chartType) {#isChartTypeBar-int-}
```
public static boolean isChartTypeBar(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Bar. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.ClusteredBar](../../com.aspose.slides/charttype\#ClusteredBar), [ChartType.ClusteredBar3D](../../com.aspose.slides/charttype\#ClusteredBar3D), [ChartType.PercentsStackedBar](../../com.aspose.slides/charttype\#PercentsStackedBar), [ChartType.PercentsStackedBar3D](../../com.aspose.slides/charttype\#PercentsStackedBar3D), [ChartType.StackedBar](../../com.aspose.slides/charttype\#StackedBar), [ChartType.StackedBar3D](../../com.aspose.slides/charttype\#StackedBar3D), [ChartType.ClusteredHorizontalCone](../../com.aspose.slides/charttype\#ClusteredHorizontalCone), [ChartType.ClusteredHorizontalCylinder](../../com.aspose.slides/charttype\#ClusteredHorizontalCylinder), [ChartType.ClusteredHorizontalPyramid](../../com.aspose.slides/charttype\#ClusteredHorizontalPyramid), [ChartType.StackedHorizontalCone](../../com.aspose.slides/charttype\#StackedHorizontalCone), [ChartType.StackedHorizontalCylinder](../../com.aspose.slides/charttype\#StackedHorizontalCylinder), [ChartType.StackedHorizontalPyramid](../../com.aspose.slides/charttype\#StackedHorizontalPyramid), [ChartType.PercentsStackedHorizontalCone](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCone), [ChartType.PercentsStackedHorizontalCylinder](../../com.aspose.slides/charttype\#PercentsStackedHorizontalCylinder), [ChartType.PercentsStackedHorizontalPyramid](../../com.aspose.slides/charttype\#PercentsStackedHorizontalPyramid).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeArea(int chartType) {#isChartTypeArea-int-}
```
public static boolean isChartTypeArea(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Area. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.Area](../../com.aspose.slides/charttype\#Area), [ChartType.PercentsStackedArea](../../com.aspose.slides/charttype\#PercentsStackedArea), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D), [ChartType.StackedArea](../../com.aspose.slides/charttype\#StackedArea), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeScatter(int chartType) {#isChartTypeScatter-int-}
```
public static boolean isChartTypeScatter(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Scatter. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.ScatterWithMarkers](../../com.aspose.slides/charttype\#ScatterWithMarkers), [ChartType.ScatterWithSmoothLines](../../com.aspose.slides/charttype\#ScatterWithSmoothLines), [ChartType.ScatterWithSmoothLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithSmoothLinesAndMarkers), [ChartType.ScatterWithStraightLines](../../com.aspose.slides/charttype\#ScatterWithStraightLines), [ChartType.ScatterWithStraightLinesAndMarkers](../../com.aspose.slides/charttype\#ScatterWithStraightLinesAndMarkers).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeStock(int chartType) {#isChartTypeStock-int-}
```
public static boolean isChartTypeStock(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Stock. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.HighLowClose](../../com.aspose.slides/charttype\#HighLowClose), [ChartType.OpenHighLowClose](../../com.aspose.slides/charttype\#OpenHighLowClose), [ChartType.VolumeHighLowClose](../../com.aspose.slides/charttype\#VolumeHighLowClose), [ChartType.VolumeOpenHighLowClose](../../com.aspose.slides/charttype\#VolumeOpenHighLowClose).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeSurface(int chartType) {#isChartTypeSurface-int-}
```
public static boolean isChartTypeSurface(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Surface. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.Surface3D](../../com.aspose.slides/charttype\#Surface3D), [ChartType.WireframeSurface3D](../../com.aspose.slides/charttype\#WireframeSurface3D), [ChartType.Contour](../../com.aspose.slides/charttype\#Contour), [ChartType.WireframeContour](../../com.aspose.slides/charttype\#WireframeContour).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeDoughnut(int chartType) {#isChartTypeDoughnut-int-}
```
public static boolean isChartTypeDoughnut(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Doughnut. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.Doughnut](../../com.aspose.slides/charttype\#Doughnut), [ChartType.ExplodedDoughnut](../../com.aspose.slides/charttype\#ExplodedDoughnut).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeBubble(int chartType) {#isChartTypeBubble-int-}
```
public static boolean isChartTypeBubble(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Bubble. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.Bubble](../../com.aspose.slides/charttype\#Bubble), [ChartType.BubbleWith3D](../../com.aspose.slides/charttype\#BubbleWith3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isChartTypeRadar(int chartType) {#isChartTypeRadar-int-}
```
public static boolean isChartTypeRadar(int chartType)
```


คืนค่า true หาก chartType เป็นหนึ่งใน subtypes ของ Radar. ชุด subtypes ตรงกับชุดที่ใช้ใน PowerPoint (ดูกล่องโต้ตอบ “Change Chart Type” ใน PowerPoint): [ChartType.FilledRadar](../../com.aspose.slides/charttype\#FilledRadar), [ChartType.Radar](../../com.aspose.slides/charttype\#Radar), [ChartType.RadarWithMarkers](../../com.aspose.slides/charttype\#RadarWithMarkers).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartType | int |  |

**ผลลัพธ์:**
boolean
### isSeriesUsesXValueCoordinate(int seriesType) {#isSeriesUsesXValueCoordinate-int-}
```
public static boolean isSeriesUsesXValueCoordinate(int seriesType)
```


คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า X.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if uses otherwise false.
### isSeriesUsesYValueCoordinate(int seriesType) {#isSeriesUsesYValueCoordinate-int-}
```
public static boolean isSeriesUsesYValueCoordinate(int seriesType)
```


คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า Y.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if uses otherwise false.
### isSeriesUsesValueCoordinate(int seriesType) {#isSeriesUsesValueCoordinate-int-}
```
public static boolean isSeriesUsesValueCoordinate(int seriesType)
```


คืนค่า true หาก series type ที่ระบุใช้พิกัดค่า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if uses otherwise false.
### isSeriesUsesBubbleSizeCoordinate(int seriesType) {#isSeriesUsesBubbleSizeCoordinate-int-}
```
public static boolean isSeriesUsesBubbleSizeCoordinate(int seriesType)
```


คืนค่า true หากพิกัดขนาดบับเบิลสามารถใช้ได้กับ series type ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if can be used, otherwise false.
### hasSeriesTrendLines(int seriesType) {#hasSeriesTrendLines-int-}
```
public static boolean hasSeriesTrendLines(int seriesType)
```


คืนค่า true หากมีเส้นแนวโน้มของ series สำหรับ series type ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if present otherwise false.
### isErrorBarsXAllowed(int seriesType) {#isErrorBarsXAllowed-int-}
```
public static boolean isErrorBarsXAllowed(int seriesType)
```


คืนค่า true หากแถบความผิดพลาด X ได้รับอนุญาตสำหรับ series type ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if allowed, otherwise false.
### isErrorBarsYAllowed(int seriesType) {#isErrorBarsYAllowed-int-}
```
public static boolean isErrorBarsYAllowed(int seriesType)
```


คืนค่า true หากแถบความผิดพลาด Y ได้รับอนุญาตสำหรับ series type ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| seriesType | int | Series type. |

**ผลลัพธ์:**
boolean - True if allowed, otherwise false.