---
title: ChartSeries
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นตัวแทนของ series ของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartseries/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

เป็น series ของแผนภูมิ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนค่าแผนภูมิแม่. |
| [getExplosion()](#getExplosion--) | ระยะของชิ้นพายที่เปิดจากศูนย์ของแผนภูมิเพียวแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระยะของชิ้นพายที่เปิดจากศูนย์ของแผนภูมิเพียวแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [getSmooth()](#getSmooth--) | แสดงการเรียบโค้ง. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | แสดงการเรียบโค้ง. |
| [getName()](#getName--) | คืนชื่อ series. |
| [getDataPoints()](#getDataPoints--) | คืนคอลเลกชันของจุดข้อมูลของ series นี้. |
| [getType()](#getType--) | คืนประเภทของ series นี้. |
| [setType(int value)](#setType-int-) | คืนประเภทของ series นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | ระบุว่า series นี้ถูกวาดบนแกนรองหรือไม่. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | ระบุว่า series นี้ถูกวาดบนแกนรองหรือไม่. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | คืนรูปแบบของ series. |
| [getOrder()](#getOrder--) | คืนลำดับของ series. |
| [setOrder(int value)](#setOrder-int-) | คืนลำดับของ series. |
| [getLabels()](#getLabels--) | คืน Labels ของ series. |
| [getTrendLines()](#getTrendLines--) | คอลเลกชันของเส้นแนวโน้มของ series. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | แสดง ErrorBars ของ series ที่มีทิศทาง X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | แสดง ErrorBars ของ series ที่มีทิศทาง Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงรายการ legend ที่เกี่ยวข้องกับ series นี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | ระบุรูปร่างของ series ของแผนภูมิแท่ง 3 มิติ. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | ระบุรูปร่างของ series ของแผนภูมิแท่ง 3 มิติ. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่า series แท่ง, คอลัมน์ หรือบับเบิลจะกลับสีหากค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่า series แท่ง, คอลัมน์ หรือบับเบิลจะกลับสีหากค่าติดลบ. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | ระบุการกลับสีทึบของ series. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | คืนค่าสีอัตโนมัติของ series ตามดัชนี series และสไตล์แผนภูมิ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | แสดงจุดภายใน. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | แสดงจุดภายใน. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | แสดงจุดนอกกฎ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | แสดงจุดนอกกฎ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | แสดงเครื่องหมายค่าเฉลี่ย. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | แสดงเครื่องหมายค่าเฉลี่ย. |
| [getShowMeanLine()](#getShowMeanLine--) | แสดงเส้นค่าเฉลี่ย. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | แสดงเส้นค่าเฉลี่ย. |
| [getQuartileMethod()](#getQuartileMethod--) | แสดงวิธีควอไทล์. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | แสดงวิธีควอไทล์. |
| [getShowConnectorLines()](#getShowConnectorLines--) | แสดงเส้นเชื่อมต่อ. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | แสดงเส้นเชื่อมต่อ. |
| [getParentLabelLayout()](#getParentLabelLayout--) | แสดงเค้าโครงของป้ายชื่อหมวดหมู่แม่. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | แสดงเค้าโครงของป้ายชื่อหมวดหมู่แม่. |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. |
| [getGapWidth()](#getGapWidth--) | ระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | คืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง series ของข้อมูลในแผนภูมิ 3 มิติ. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ระบุมุมของสไลซ์แรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, 0 ถึง 360 องศา). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่แผนภูมิ). |
| [getOverlap()](#getOverlap--) | ระบุว่าบาร์และคอลัมน์ทับกันบนแผนภูมิ 2 มิติเท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [hasSeriesLines()](#hasSeriesLines--) | กำหนดว่ามีเส้น series สำหรับ series นี้และ series ที่เกี่ยวข้องหรือไม่. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุว่าค่าขนาดบับเบิลจะแสดงบนแผนภูมิบับเบิลอย่างไร. |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแบ่งแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแบ่งแบบกำหนดเอง. |
| [isColorVaried()](#isColorVaried--) | ระบุว่าแต่ละ marker ของข้อมูลใน series มีสีต่างกัน. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุตัวคูณสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

ระยะของชิ้นพายที่เปิดจากศูนย์ของแผนภูมิเพียวแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน-เขียน int.

**คืนค่า:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

ระยะของชิ้นพายที่เปิดจากศูนย์ของแผนภูมิเพียวแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน-เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

แสดงการเรียบโค้ง. จริงถ้าเปิดการเรียบโค้งสำหรับแผนภูมิแบบเส้นหรือกระจาย. ใช้ได้เฉพาะแผนภูมิแบบเส้นและกระจายที่เชื่อมด้วยเส้น. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

แสดงการเรียบโค้ง. จริงถ้าเปิดการเรียบโค้งสำหรับแผนภูมิแบบเส้นหรือกระจาย. ใช้ได้เฉพาะแผนภูมิแบบเส้นและกระจายที่เชื่อมด้วยเส้น. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

คืนชื่อ series. อ่านอย่างเดียว [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**คืนค่า:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

คืนคอลเลกชันของจุดข้อมูลของ series นี้. อ่านอย่างเดียว [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**คืนค่า:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

คืนประเภทของ series นี้. อ่าน-เขียน [ChartType](../../com.aspose.slides/charttype).

**คืนค่า:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

คืนประเภทของ series นี้. อ่าน-เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

ระบุว่า series นี้ถูกวาดบนแกนรองหรือไม่. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

ระบุว่า series นี้ถูกวาดบนแกนรองหรือไม่. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. อ่านอย่างเดียว [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**คืนค่า:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

คืนรูปแบบของ series. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

คืนลำดับของ series. อ่าน-เขียน int.

**คืนค่า:**  
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

คืนลำดับของ series. อ่าน-เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

คืน Labels ของ series. อ่านอย่างเดียว [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**คืนค่า:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

คอลเลกชันของเส้นแนวโน้มของ series. อ่านอย่างเดียว [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines are available (not null) for data series in unstacked 2-D area, bar, column, line, stock, xy (scatter), and bubble charts. A trendline are not available for data series in any chart type that is stacked or 3-D. Trendlines are also not available for radar, pie, surface, or doughnut charts.

**คืนค่า:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

แสดง ErrorBars ของ series ที่มีทิศทาง X. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**คืนค่า:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

แสดง ErrorBars ของ series ที่มีทิศทาง Y. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**คืนค่า:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

แสดงรายการ legend ที่เกี่ยวข้องกับ series นี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. อ่าน-เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. อ่าน-เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. อ่าน-เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. อ่าน-เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. อ่าน-เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. อ่าน-เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. อ่าน-เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. อ่าน-เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

ระบุรูปร่างของ series ของแผนภูมิแท่ง 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ Type ของ series เปลี่ยนอัตโนมัติ. อ่าน-เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**คืนค่า:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

ระบุรูปร่างของ series ของแผนภูมิแท่ง 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ Type ของ series เปลี่ยนอัตโนมัติ. อ่าน-เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

ระบุว่า series แท่ง, คอลัมน์ หรือบับเบิลจะกลับสีหากค่าติดลบ. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

ระบุว่า series แท่ง, คอลัมน์ หรือบับเบิลจะกลับสีหากค่าติดลบ. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

ระบุการกลับสีทึบของ series. เพื่อใช้การตั้งค่าสีให้ตั้ง FillType ของรูปแบบ series เป็น FillType.Solid. อ่าน-เขียน [ColorFormat](../../com.aspose.slides/colorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

คืนค่าสีอัตโนมัติของ series ตามดัชนี series และสไตล์แผนภูมิ. สีนี้ใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**  
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

แสดงจุดภายใน. จริงถ้าแสดงจุดภายในบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

แสดงจุดภายใน. จริงถ้าแสดงจุดภายในบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

แสดงจุดนอกกฎ. จริงถ้าแสดงจุดนอกกฎบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

แสดงจุดนอกกฎ. จริงถ้าแสดงจุดนอกกฎบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าแสดงเครื่องหมายค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าแสดงเครื่องหมายค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

แสดงเส้นค่าเฉลี่ย. จริงถ้าแสดงเส้นค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**คืนค่า:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

แสดงเส้นค่าเฉลี่ย. จริงถ้าแสดงเส้นค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน-เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

แสดงวิธีควอไทล์. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker.

**คืนค่า:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

แสดงวิธีควอไทล์. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall.

**คืนค่า:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

แสดงเค้าโครงของป้ายชื่อหมวดหมู่แม่. ใช้ได้เฉพาะแผนภูมิ Treemap.

**คืนค่า:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

แสดงเค้าโครงของป้ายชื่อหมวดหมู่แม่. ใช้ได้เฉพาะแผนภูมิ Treemap.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series แม่. ใช้ ParentSeriesGroup.UpDownBars.HasUpDownBars เพื่อเปลี่ยนค่า. ใช้ ParentSeriesGroup.UpDownBars เพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**คืนค่า:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

ระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series แม่. ใช้ ParentSeriesGroup.GapWidth เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**คืนค่า:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

คืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง series ของข้อมูลในแผนภูมิ 3 มิติ. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series แม่. ใช้ ParentSeriesGroup.GapDepth เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**คืนค่า:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

ระบุมุมของสไลซ์แรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, 0 ถึง 360 องศา). คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series แม่. ใช้ ParentSeriesGroup.FirstSliceAngle เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**คืนค่า:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่แผนภูมิ.). คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series แม่. ใช้ ParentSeriesGroup.DoughnutHoleSize เพื่อเปลี่ยนค่า. อ่านอย่างเดียว byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**คืนค่า:**  
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

ระบุว่าบาร์และคอลัมน์ทับกันบนแผนภูมิ 2 มิติเท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่. มันเป็นการฉายของคุณสมบัติเกี่ยวกับกลุ่ม series แม่, จึงเป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่าให้ใช้ ParentSeriesGroup.Overlap. อ่านอย่างเดียว byte.

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**คืนค่า:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.SecondPieSize เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**คืนค่า:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

กำหนดว่ามีเส้น series สำหรับ series นี้และ series ที่เกี่ยวข้องหรือไม่. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.HasSeriesLines เพื่อเปลี่ยนค่า. ใช้ ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้น series. อ่านอย่างเดียว boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**คืนค่า:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

ระบุว่าค่าขนาดบับเบิลจะแสดงบนแผนภูมิบับเบิลอย่างไร. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.BubbleSizeRepresentation เพื่อเปลี่ยนค่า.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**คืนค่า:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.PieSplitPosition เพื่อเปลี่ยนค่า. อ่านอย่างเดียว double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**คืนค่า:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.PieSplitBy เพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**คืนค่า:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแบ่งแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแบ่งแบบกำหนดเอง. มีจุดข้อมูลที่จะวาดในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม อ่านอย่างเดียว [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**คืนค่า:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

ระบุว่าแต่ละ marker ของข้อมูลใน series มีสีต่างกัน. คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.IsColorVaried เพื่อเปลี่ยนค่า. อ่านอย่างเดียว boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**คืนค่า:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

ระบุตัวคูณสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). คุณสมบัตินี้ไม่ใช่ของ series นี้เพียงอย่างเดียวแต่ของทุก series ในกลุ่ม series แม่ – เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. จึงเป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup.BubbleSizeScale เพื่อเปลี่ยนค่า.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**คืนค่า:**  
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)