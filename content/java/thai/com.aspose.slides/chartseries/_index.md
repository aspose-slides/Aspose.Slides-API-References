---
title: ChartSeries
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของชุดข้อมูลแผนภูมิ
type: docs
url: /th/com.aspose.slides/chartseries/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Represents a chart series.  
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนแผนภูมิแม่. |
| [getExplosion()](#getExplosion--) | ระยะห่างของชั้นพายที่เปิดจากศูนย์ของแผนภูมิพายเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระยะห่างของชั้นพายที่เปิดจากศูนย์ของแผนภูมิพายเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [getSmooth()](#getSmooth--) | อธิบายการทำให้เส้นโค้งเรียบ. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | อธิบายการทำให้เส้นโค้งเรียบ. |
| [getName()](#getName--) | คืนชื่อซีรีส์. |
| [getDataPoints()](#getDataPoints--) | คืนคอลเลกชันของจุดข้อมูลของซีรีส์นี้. |
| [getType()](#getType--) | คืนชนิดของซีรีส์นี้. |
| [setType(int value)](#setType-int-) | คืนชนิดของซีรีส์นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | ระบุว่าซีรีส์นี้ถูกพล็อตบนแกนรองหรือไม่. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | ระบุว่าซีรีส์นี้ถูกพล็อตบนแกนรองหรือไม่. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | คืนรูปแบบของซีรีส์. |
| [getOrder()](#getOrder--) | คืนลำดับของซีรีส์. |
| [setOrder(int value)](#setOrder-int-) | คืนลำดับของซีรีส์. |
| [getLabels()](#getLabels--) | คืนป้ายชื่อของซีรีส์. |
| [getTrendLines()](#getTrendLines--) | คอลเลกชันของเส้นแนวโน้มของซีรีส์. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | อธิบาย ErrorBars ของซีรีส์ที่มีทิศทาง X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | อธิบาย ErrorBars ของซีรีส์ที่มีทิศทาง Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | อธิบายรายการคติกที่เกี่ยวข้องกับซีรีส์นี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3-มิติ. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3-มิติ. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าแท่ง, คอลัมน์ หรือซีรีส์บับเบิลจะสลับสีหากค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าแท่ง, คอลัมน์ หรือซีรีส์บับเบิลจะสลับสีหากค่าติดลบ. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | ระบุการสลับสีทึบสำหรับซีรีส์. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | คืนสีอัตโนมัติของซีรีส์ตามดัชนีซีรีส์และสไตล์แผนภูมิ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | อธิบายจุดภายใน. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | อธิบายจุดภายใน. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | อธิบายจุดนอกเหนือ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | อธิบายจุดนอกเหนือ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | อธิบายเครื่องหมายค่าเฉลี่ย. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | อธิบายเครื่องหมายค่าเฉลี่ย. |
| [getShowMeanLine()](#getShowMeanLine--) | อธิบายเส้นค่าเฉลี่ย. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | อธิบายเส้นค่าเฉลี่ย. |
| [getQuartileMethod()](#getQuartileMethod--) | อธิบายวิธีควอร์ไทล์. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | อธิบายวิธีควอร์ไทล์. |
| [getShowConnectorLines()](#getShowConnectorLines--) | อธิบายเส้นเชื่อมต่อ. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | อธิบายเส้นเชื่อมต่อ. |
| [getParentLabelLayout()](#getParentLabelLayout--) | อธิบายการจัดวางป้ายชื่อหมวดแม่. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | อธิบายการจัดวางป้ายชื่อหมวดแม่. |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. |
| [getGapWidth()](#getGapWidth--) | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | คืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ระบุมุมของชิ้นพายหรือโดนัทชิ้นแรกในองศา (ตามเข็มนาฬิกาตั้งแต่บน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 10% ถึง 90% ของขนาดพื้นที่แผนภูมิ). |
| [getOverlap()](#getOverlap--) | ระบุว่าบาร์และคอลัมน์ทับกันบนแผนภูมิ 2-มิติเท่าใดเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5% ถึง 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | กำหนดว่ามีเส้นซีรีส์สำหรับซีรีส์นี้และซีรีส์ที่เกี่ยวข้องหรือไม่. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุวิธีที่ค่าขนาดบับเบิลแสดงบนแผนภูมิบับเบิล. |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลไหนอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีที่ค่าจะกำหนดว่าจุดข้อมูลไหนอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกกำหนดเอง. |
| [isColorVaried()](#isColorVaried--) | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีต่างกัน. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0% ถึง 300% ของขนาดเริ่มต้น). |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

ระยะห่างของชั้นพายที่เปิดจากศูนย์ของแผนภูมิพายเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน int.

**คืนค่า:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

ระยะห่างของชั้นพายที่เปิดจากศูนย์ของแผนภูมิพายเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

อธิบายการทำให้เส้นโค้งเรียบ. True ถ้าการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้เฉพาะแผนภูมิไลน์และกระจายที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

อธิบายการทำให้เส้นโค้งเรียบ. True ถ้าการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้เฉพาะแผนภูมิไลน์และกระจายที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

คืนชื่อซีรีส์. อ่านอย่างเดียว [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**คืนค่า:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

คืนคอลเลกชันของจุดข้อมูลของซีรีส์นี้. อ่านอย่างเดียว [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**คืนค่า:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

คืนชนิดของซีรีส์นี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**คืนค่า:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

คืนชนิดของซีรีส์นี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

ระบุว่าซีรีส์นี้ถูกพล็อตบนแกนรองหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

ระบุว่าซีรีส์นี้ถูกพล็อตบนแกนรองหรือไม่. อ่าน/เขียน boolean.

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

คืนรูปแบบของซีรีส์. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

คืนลำดับของซีรีส์. อ่าน/เขียน int.

**คืนค่า:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

คืนลำดับของซีรีส์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

คืนป้ายชื่อของซีรีส์. อ่านอย่างเดียว [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**คืนค่า:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

คอลเลกชันของเส้นแนวโน้มของซีรีส์. อ่านอย่างเดียว [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines are available (not null) for data series in unstacked 2-D area, bar, column, line, stock, xy (scatter), and bubble charts. A trendline are not available for data series in any chart type that is stacked or 3-D. Trendlines are also not available for radar, pie, surface, or doughnut charts.

**คืนค่า:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

อธิบาย ErrorBars ของซีรีส์ที่มีทิศทาง X. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**คืนค่า:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

อธิบาย ErrorBars ของซีรีส์ที่มีทิศทาง Y. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**คืนค่า:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

อธิบายรายการคติกที่เกี่ยวข้องกับซีรีส์นี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. อ่าน/เขียน String.

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

ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3-มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ชนิดของซีรีส์เปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**คืนค่า:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3-มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ชนิดของซีรีส์เปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

ระบุว่าแท่ง, คอลัมน์ หรือซีรีส์บับเบิลจะสลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

ระบุว่าแท่ง, คอลัมน์ หรือซีรีส์บับเบิลจะสลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
ระบุสีของ solid แบบกลับค่าสำหรับ series. เพื่อใช้การตั้งค่าสีให้ตั้งค่า FillType ของ series format เป็น FillType.Solid. อ่าน/เขียน [ColorFormat](../../com.aspose.slides/colorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

คืนค่าสีอัตโนมัติของ series ตามดัชนี series และสไตล์แผนภูมิ. สีนี้จะถูกใช้โดยค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**
java.awt.Color - อ็อบเจ็กต์ java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

แสดงจุดภายใน. true หากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

ตั้งค่าให้แสดงจุดภายใน. true หากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

แสดงจุดนอกกลุ่ม. true หากจุดนอกกลุ่มแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

ตั้งค่าให้แสดงจุดนอกกลุ่ม. true หากจุดนอกกลุ่มแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

แสดงเครื่องหมายค่าเฉลี่ย. true หากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

ตั้งค่าให้แสดงเครื่องหมายค่าเฉลี่ย. true หากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

แสดงเส้นค่าเฉลี่ย. true หากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

ตั้งค่าให้แสดงเส้นค่าเฉลี่ย. true หากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

ระบุวิธีการคำนวณควอไทล์. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น.

**คืนค่า:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

ตั้งค่าวิธีการคำนวณควอไทล์. ใช้กับแผนภูมิ BoxAndWhisker เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

แสดงเส้นเชื่อมต่อ. ใช้กับแผนภูมิ Waterfall เท่านั้น.

**คืนค่า:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

ตั้งค่าให้แสดงเส้นเชื่อมต่อ. ใช้กับแผนภูมิ Waterfall เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

ระบุการจัดวางป้ายชื่อหมวดแม่. ใช้กับแผนภูมิ Treemap เท่านั้น.

**คืนค่า:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

ตั้งค่าการจัดวางป้ายชื่อหมวดแม่. ใช้กับแผนภูมิ Treemap เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars เพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars.

**คืนค่า:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.GapWidth.

**คืนค่า:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ระหว่าง series ของข้อมูลในแผนภูมิ 3D. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.GapDepth.

**คืนค่า:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

ระบุมุมของชิ้นแรกของแผนภูมิปายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศ). นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.FirstSliceAngle.

**คืนค่า:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ระบุขนาดของหลุมในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10% ถึง 90% ของขนาดพื้นที่พล็อต). นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว byte.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.DoughnutHoleSize.

**คืนค่า:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

ระบุว่าบาร์และคอลัมน์ทับกันบนแผนภูมิ 2-D เท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่. เป็นการฉายภาพของคุณสมบัติในกลุ่ม series พ่อแม่, ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่า, ใช้คุณสมบัติ ParentSeriesGroup.Overlap อ่าน/เขียน. อ่านอย่างเดียว byte.

--------------------

Overlap ระบุระดับการทับหรือช่องว่างระหว่างบาร์และคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของพวกมัน: -100%: ช่องว่างสูงสุด (บาร์แยกจากกันทั้งหมด). 0%: บาร์วางเคียงกันโดยไม่มีการทับหรือช่องว่าง. 100%: การทับสูงสุด (บาร์ทับซ้อนกันทั้งหมด). นี่เป็นการฉายภาพของคุณสมบัติ ParentSeriesGroup.Overlap.

**คืนค่า:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5% ถึง 200%). นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.SecondPieSize.

**คืนค่า:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

กำหนดว่ามีเส้น series สำหรับ series นี้และ series ที่เกี่ยวข้องหรือไม่. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้น series. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.HasSeriesLines.

**คืนค่า:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

ระบุว่าค่า size ของบับเบิลจะแสดงอย่างไรบนแผนภูมิบับเบิล. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียนเพื่อเปลี่ยนค่า.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation.

**คืนค่า:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

ระบุตำแหน่งค่าที่ใช้กำหนดว่าข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว double.

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.PieSplitPosition.

**คืนค่า:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

ระบุวิธีกำหนดว่าข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พ่อแม่. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.PieSplitBy. 2) หากค่าคุณสมบัติเป็น PieSplitType.Custom คุณสามารถกำหนดข้อมูลการแยกแบบกำหนดเองด้วยคุณสมบัติ ParentSeriesGroup.PieSplitCustomPoints.

**คืนค่า:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือบาร์ที่สองของแผนภูมิ. นี่เป็นคุณสมบัติของไม่เฉพาะ series นี้เท่านั้น แต่ของ series ทั้งหมดในกลุ่ม series พ่อแม่ – เป็นการฉายภาพของคุณสมบัติกลุ่มที่เกี่ยวข้อง อ่านอย่างเดียว [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

นี่คือการฉายภาพของคุณสมบัติ ParentSeriesGroup.PieSplitCustomPoints.

**คืนค่า:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในชุดข้อมูลมีสีที่แตกต่างกัน. นี้เป็นคุณสมบัติไม่เฉพาะของชุดข้อมูลนี้เท่านั้น แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ - นี่เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried แบบอ่าน/เขียนเพื่อเปลี่ยนค่า. Boolean แบบอ่านอย่างเดียว.

--------------------

นี่เป็นการฉายของคุณสมบัติ ParentSeriesGroup.IsColorVaried.

**คืนค่า:**  
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

ระบุอัตราสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). นี้เป็นคุณสมบัติไม่เฉพาะของชุดข้อมูลนี้เท่านั้น แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ - นี่เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScaleแบบอ่าน/เขียนเพื่อเปลี่ยนค่า.

--------------------

นี่เป็นการฉายของคุณสมบัติ ParentSeriesGroup.BubbleSizeScale.

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

คืนพรีเซนเทชันแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)