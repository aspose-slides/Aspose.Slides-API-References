---
title: IChartSeries
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงชุดข้อมูลของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.  
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExplosion()](#getExplosion--) | ระยะของชิ้นส่วนพายที่เปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระยะของชิ้นส่วนพายที่เปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. |
| [getSmooth()](#getSmooth--) | แสดงถึงการทำให้เส้นโค้งเรียบ. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | แสดงถึงการทำให้เส้นโค้งเรียบ. |
| [getMarker()](#getMarker--) | ส่งคืนตัวบ่งชี้ชุดข้อมูล. |
| [getBar3DShape()](#getBar3DShape--) | ระบุรูปร่างของชุดข้อมูลของแผนภูมิบาร์ 3-มิติ. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | ระบุรูปร่างของชุดข้อมูลของแผนภูมิบาร์ 3-มิติ. |
| [getName()](#getName--) | ส่งคืนชื่อชุดข้อมูล. |
| [getDataPoints()](#getDataPoints--) | ส่งคืนคอลเลกชันของจุดข้อมูลของชุดนี้. |
| [getType()](#getType--) | ส่งคืนประเภทของชุดนี้. |
| [setType(int value)](#setType-int-) | ส่งคืนประเภทของชุดนี้. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ส่งคืนกลุ่มชุดข้อมูลแม่. |
| [getFormat()](#getFormat--) | ส่งคืนรูปแบบของชุดข้อมูล. |
| [getOrder()](#getOrder--) | ส่งคืนลำดับของชุดข้อมูล. |
| [setOrder(int value)](#setOrder-int-) | ส่งคืนลำดับของชุดข้อมูล. |
| [getLabels()](#getLabels--) | ส่งคืนป้ายชื่อของชุดข้อมูล. |
| [getTrendLines()](#getTrendLines--) | คอลเลกชันของเส้นแนวโน้มของชุดข้อมูล อ่านอย่างเดียว [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | แสดงถึง ErrorBars ของชุดข้อมูลที่มีทิศทาง X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | แสดงถึง ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | บ่งชี้ว่าชุดข้อมูลนี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | บ่งชี้ว่าชุดข้อมูลนี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของชุดข้อมูล. อ่าน/เขียน String. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่ของชุดข้อมูล. อ่าน/เขียน String. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของชุดข้อมูล. อ่าน/เขียน String. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของชุดข้อมูล. อ่าน/เขียน String. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของชุดข้อมูล. อ่าน/เขียน String. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของชุดข้อมูล. อ่าน/เขียน String. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุดข้อมูล. อ่าน/เขียน String. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุดข้อมูล. อ่าน/เขียน String. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าบาร์, คอลัมน์ หรือชุดข้อมูลบับเบิลจะต้องกลับสีถ้าค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าบาร์, คอลัมน์ หรือชุดข้อมูลบับเบิลจะต้องกลับสีถ้าค่าติดลบ. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | ระบุการกลับสีของโซลิดสำหรับชุดข้อมูล. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงถึงรายการคำอธิบายที่เกี่ยวข้องกับชุดข้อมูลนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | ส่งคืนสีอัตโนมัติของชุดข้อมูลตามดัชนีชุดข้อมูลและสไตล์ของแผนภูมิ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | แสดงถึงจุดภายใน. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | แสดงถึงจุดภายใน. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | แสดงถึงจุดนอกเกณฑ์. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | แสดงถึงจุดนอกเกณฑ์. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. |
| [getShowMeanLine()](#getShowMeanLine--) | แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. |
| [getQuartileMethod()](#getQuartileMethod--) | แสดงถึงวิธีควอร์ไทล์. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | แสดงถึงวิธีควอร์ไทล์. |
| [getShowConnectorLines()](#getShowConnectorLines--) | แสดงถึงเส้นเชื่อม. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | แสดงถึงเส้นเชื่อม. |
| [getParentLabelLayout()](#getParentLabelLayout--) | แสดงถึงการจัดวางของป้ายชื่อหมวดแม่. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | แสดงถึงการจัดวางของป้ายชื่อหมวดแม่. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุสเกลแฟคเตอร์สำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. |
| [getGapWidth()](#getGapWidth--) | ระบุช่องว่างระหว่างคลัสเตอร์ของบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | ส่งคืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างตัวบ่งชี้ระหว่างชุดข้อมูลในแผนภูมิ 3D. |
| [isColorVaried()](#isColorVaried--) | ระบุว่าตัวบ่งชี้ข้อมูลแต่ละตัวในชุดข้อมูลจะมีสีต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดนี้และชุดที่เกี่ยวข้องหรือไม่. |
| [getOverlap()](#getOverlap--) | ระบุว่าบาร์และคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ระบุมุมของชิ้นส่วนแรกของพายหรือแผนภูมิโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุว่าค่าขนาดบับเบิลจะแสดงอย่างไรบนแผนภูมิบับเบิล. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

ระยะของชิ้นส่วนพายที่เปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. อ่าน/เขียน int.

**Returns:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

ระยะของชิ้นส่วนพายที่เปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. อ่าน/เขียน int.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

แสดงถึงการทำให้เส้นโค้งเรียบ. true หากการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้กับแผนภูมิเส้นและแผนภูมิกระจายที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

แสดงถึงการทำให้เส้นโค้งเรียบ. true หากการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้กับแผนภูมิเส้นและแผนภูมิกระจายที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

ส่งคืนตัวบ่งชี้ชุดข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**Returns:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

ระบุรูปร่างของชุดข้อมูลของแผนภูมิบาร์ 3-มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

ระบุรูปร่างของชุดข้อมูลของแผนภูมิบาร์ 3-มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

ส่งคืนชื่อชุดข้อมูล. อ่านอย่างเดียว [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

ส่งคืนคอลเลกชันของจุดข้อมูลของชุดนี้. อ่านอย่างเดียว [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

ส่งคืนประเภทของชุดนี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**Returns:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

ส่งคืนประเภทของชุดนี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

ส่งคืนกลุ่มชุดข้อมูลแม่. อ่านอย่างเดียว [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ส่งคืนรูปแบบของชุดข้อมูล. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**Returns:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

ส่งคืนลำดับของชุดข้อมูล. อ่าน/เขียน int.

**Returns:**  
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

ส่งคืนลำดับของชุดข้อมูล. อ่าน/เขียน int.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

ส่งคืนป้ายชื่อของชุดข้อมูล. อ่านอย่างเดียว [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

คอลเลกชันของเส้นแนวโน้มของชุดข้อมูล อ่านอย่างเดียว [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returns:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

แสดงถึง ErrorBars ของชุดข้อมูลที่มีทิศทาง X. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars ที่มีทิศทาง X มีให้ใช้สำหรับชุดข้อมูลชนิด area, bar, scatter และ bubble. สำหรับชนิดแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). หากต้องการค่ากำหนดเองให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Returns:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

แสดงถึง ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars ที่มีทิศทาง Y มีให้ใช้สำหรับชุดข้อมูลชนิด area, bar, line, scatter และ bubble. สำหรับชนิดแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). หากต้องการค่ากำหนดเองให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Returns:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

บ่งชี้ว่าชุดข้อมูลนี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

บ่งชี้ว่าชุดข้อมูลนี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของชุดข้อมูล. อ่าน/เขียน String.

**Returns:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของชุดข้อมูล. อ่าน/เขียน String.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของชุดข้อมูล. อ่าน/เขียน String.

**Returns:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของชุดข้อมูล. อ่าน/เขียน String.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของชุดข้อมูล. อ่าน/เขียน String.

**Returns:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของชุดข้อมูล. อ่าน/เขียน String.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุดข้อมูล. อ่าน/เขียน String.

**Returns:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุดข้อมูล. อ่าน/เขียน String.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

ระบุว่าบาร์, คอลัมน์ หรือชุดข้อมูลบับเบิลจะต้องกลับสีถ้าค่าติดลบ. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

ระบุว่าบาร์, คอลัมน์ หรือชุดข้อมูลบับเบิลจะต้องกลับสีถ้าค่าติดลบ. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

ระบุการกลับสีของโซลิดสำหรับชุดข้อมูล. เพื่อใช้การตั้งค่าสีให้ตั้งค่า FillType ของรูปแบบชุดข้อมูลเป็น FillType.Solid. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

แสดงถึงรายการคำอธิบายที่เกี่ยวข้องกับชุดข้อมูลนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

ส่งคืนสีอัตโนมัติของชุดข้อมูลตามดัชนีชุดข้อมูลและสไตล์ของแผนภูมิ. สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**Returns:**  
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

แสดงถึงจุดภายใน. true หากจุดภายในแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

แสดงถึงจุดภายใน. true หากจุดภายในแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

แสดงถึงจุดนอกเกณฑ์. true หากจุดนอกเกณฑ์แสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

แสดงถึงจุดนอกเกณฑ์. true หากจุดนอกเกณฑ์แสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. true หากตัวบ่งชี้ค่าเฉลี่ยแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

แสดงถึงตัวบ่งชี้ค่าเฉลี่ย. true หากตัวบ่งชี้ค่าเฉลี่ยแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

แสดงถึงเส้นค่าเฉลี่ย. true หากเส้นค่าเฉลี่ยแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Returns:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

แสดงถึงเส้นค่าเฉลี่ย. true หากเส้นค่าเฉลี่ยแสดงในแผนภูมิ BoxAndWhisker. ใช้ได้กับแผนภูมิ BoxAndWhisker. อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

แสดงถึงวิธีควอร์ไทล์. ใช้ได้กับแผนภูมิ BoxAndWhisker.

**Returns:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

แสดงถึงวิธีควอร์ไทล์. ใช้ได้กับแผนภูมิ BoxAndWhisker.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

แสดงถึงเส้นเชื่อม. ใช้ได้กับแผนภูมิ Waterfall.

**Returns:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

แสดงถึงเส้นเชื่อม. ใช้ได้กับแผนภูมิ Waterfall.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

แสดงถึงการจัดวางของป้ายชื่อหมวดแม่. ใช้ได้กับแผนภูมิ Treemap.

**Returns:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

แสดงถึงการจัดวางของป้ายชื่อหมวดแม่. ใช้ได้กับแผนภูมิ Treemap.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

ระบุสเกลแฟคเตอร์สำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.BubbleSizeScale เพื่อกำหนดค่า.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.BubbleSizeScale.

**Returns:**  
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.UpDownBars.HasUpDownBars เพื่อกำหนดค่า. ใช้ ParentSeriesGroup.UpDownBars เพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returns:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

ระบุช่องว่างระหว่างกลุ่มบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.GapWidth เพื่อกำหนดค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.GapWidth.

**Returns:**  
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

ส่งคืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างตัวบ่งชี้ระหว่างชุดข้อมูลในแผนภูมิ 3D. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.GapDepth เพื่อกำหนดค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.GapDepth.

**Returns:**  
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

ระบุว่าตัวบ่งชี้ข้อมูลแต่ละตัวในชุดข้อมูลจะมีสีต่างกัน. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.IsColorVaried เพื่อกำหนดค่า. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.IsColorVaried.

**Returns:**  
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดนี้และชุดที่เกี่ยวข้องหรือไม่. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.HasSeriesLines เพื่อกำหนดค่า. ใช้ ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้นชุดข้อมูล. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.HasSeriesLines.

**Returns:**  
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

ระบุว่าบาร์และคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่. เป็นการฉายของคุณสมบัตินั้นในกลุ่มชุดข้อมูลแม่, ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่า, ใช้ ParentSeriesGroup.Overlap เพื่อกำหนดค่า. อ่านอย่างเดียว byte.

--------------------

Overlap ระบุระดับการทับหรือช่องว่างระหว่างบาร์และคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของพวกมัน: -100%: ช่องว่างมากที่สุด (บาร์แยกจากกันอย่างสมบูรณ์). 0%: บาร์วางติดกันโดยไม่มีการทับหรือช่องว่าง. 100%: การทับสูงสุด (บาร์ทับซ้อนกันทั้งหมด). นี่เป็นการฉายของคุณสมบัติ ParentSeriesGroup.Overlap.

**Returns:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.SecondPieSize เพื่อกำหนดค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.SecondPieSize.

**Returns:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

ระบุค่าที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.PieSplitPosition เพื่อกำหนดค่า. อ่านอย่างเดียว double.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.PieSplitPosition.

**Returns:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.PieSplitBy เพื่อกำหนดค่า. อ่านอย่างเดียว [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.PieSplitBy. 2) หากค่า property เป็น PieSplitType.Custom คุณสามารถกำหนดข้อมูลการแยกแบบกำหนดเองด้วย ParentSeriesGroup.PieSplitCustomPoints.

**Returns:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.DoughnutHoleSize เพื่อกำหนดค่า. อ่านอย่างเดียว byte.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.DoughnutHoleSize.

**Returns:**  
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

ระบุมุมของชิ้นส่วนแรกของพายหรือแผนภูมิโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.FirstSliceAngle เพื่อกำหนดค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.FirstSliceAngle.

**Returns:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ต้องวาดในพายหรือบาร์ที่สองในแผนภูมิแบบนั้น. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติที่เกี่ยวข้อง. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.PieSplitCustomPoints.

**Returns:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

ระบุว่าค่าขนาดบับเบิลจะแสดงอย่างไรบนแผนภูมิบับเบิล. นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ – เป็นการฉายของคุณสมบัติที่เกี่ยวข้อง. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้ ParentSeriesGroup.BubbleSizeRepresentation เพื่อกำหนดค่า.

--------------------

นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation.

**Returns:**  
int