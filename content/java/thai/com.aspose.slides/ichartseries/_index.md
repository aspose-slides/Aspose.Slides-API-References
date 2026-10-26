---
title: IChartSeries
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของชุดข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartseries/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

เป็นตัวแทนของซีรีส์แผนภูมิ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExplosion()](#getExplosion--) | ระยะของชิ้นพายที่เปิดออกจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระยะของชิ้นพายที่เปิดออกจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. |
| [getSmooth()](#getSmooth--) | เป็นตัวแทนของการทำให้เส้นโค้งเรียบ. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | เป็นตัวแทนของการทำให้เส้นโค้งเรียบ. |
| [getMarker()](#getMarker--) | ส่งคืนตัวทำเครื่องหมายของซีรีส์. |
| [getBar3DShape()](#getBar3DShape--) | ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3 มิติ. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3 มิติ. |
| [getName()](#getName--) | ส่งคืนชื่อซีรีส์. |
| [getDataPoints()](#getDataPoints--) | ส่งคืนคอลเลกชันของจุดข้อมูลของซีรีส์นี้. |
| [getType()](#getType--) | ส่งคืนประเภทของซีรีส์นี้. |
| [setType(int value)](#setType-int-) | ส่งคืนประเภทของซีรีส์นี้. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ส่งคืนกลุ่มซีรีส์พาเรนต์. |
| [getFormat()](#getFormat--) | ส่งคืนรูปแบบของซีรีส์. |
| [getOrder()](#getOrder--) | ส่งคืนลำดับของซีรีส์. |
| [setOrder(int value)](#setOrder-int-) | ส่งคืนลำดับของซีรีส์. |
| [getLabels()](#getLabels--) | ส่งคืนป้ายชื่อของซีรีส์. |
| [getTrendLines()](#getTrendLines--) | คอลเลกชันของเส้นแนวโน้มซีรีส์ (อ่านอย่างเดียว) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | เป็นตัวแทนของ ErrorBars ของซีรีส์ที่มีทิศทาง X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | เป็นตัวแทนของ ErrorBars ของซีรีส์ที่มีทิศทาง Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | บ่งชี้ว่าซีรีส์นี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | บ่งชี้ว่าซีรีส์นี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของซีรีส์. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของซีรีส์. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด X ของซีรีส์. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด X ของซีรีส์. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด Y ของซีรีส์. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด Y ของซีรีส์. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของซีรีส์. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของซีรีส์. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าแถบ, คอลัมน์ หรือ ซีรีส์บับเบิลจะต้องกลับสีเมื่อค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าแถบ, คอลัมน์ หรือ ซีรีส์บับเบิลจะต้องกลับสีเมื่อค่าติดลบ. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | ระบุสีทึบกลับสำหรับซีรีส์. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | เป็นตัวแทนของรายการคำอธิบายที่เกี่ยวข้องกับซีรีส์นี้ (อ่านอย่างเดียว) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | ส่งคืนสีอัตโนมัติของซีรีส์ตามดัชนีซีรีส์และสไตล์แผนภูมิ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | เป็นตัวแทนของจุดภายใน. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | เป็นตัวแทนของจุดภายใน. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | เป็นตัวแทนของจุดนอกกลุ่ม (outlier). |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | เป็นตัวแทนของจุดนอกกลุ่ม (outlier). |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | เป็นตัวแทนของเครื่องหมายค่าเฉลี่ย. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | เป็นตัวแทนของเครื่องหมายค่าเฉลี่ย. |
| [getShowMeanLine()](#getShowMeanLine--) | เป็นตัวแทนของเครื่องหมายค่าเฉลี่ย. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | เป็นตัวแทนของเครื่องหมายค่าเฉลี่ย. |
| [getQuartileMethod()](#getQuartileMethod--) | เป็นตัวแทนของวิธีควอร์ไทล์. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | เป็นตัวแทนของวิธีควอร์ไทล์. |
| [getShowConnectorLines()](#getShowConnectorLines--) | เป็นตัวแทนของเส้นเชื่อมต่อ. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | เป็นตัวแทนของเส้นเชื่อมต่อ. |
| [getParentLabelLayout()](#getParentLabelLayout--) | เป็นตัวแทนของการจัดวางป้ายชื่อหมวดหมู่พาเรนต์. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | เป็นตัวแทนของการจัดวางป้ายชื่อหมวดหมู่พาเรนต์. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุค่าอัตราปรับขนาดสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่าแผนภูมิสายหรือแผนภูมิเส้นหุ้นมีแถบขึ้น/ลงหรือไม่. |
| [getGapWidth()](#getGapWidth--) | ระบุช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | ส่งคืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างเครื่องหมาย ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ. |
| [isColorVaried()](#isColorVaried--) | ระบุว่าเครื่องหมายข้อมูลแต่ละตัวในซีรีส์จะมีสีแตกต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | กำหนดว่ามีเส้นซีรีส์สำหรับซีรีส์นี้และซีรีส์ใกล้เคียงหรือไม่. |
| [getOverlap()](#getOverlap--) | ระบุว่าบาร์และคอลัมน์ทับซ้อนกันเท่าใดบนแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิพายของพายหรือแถบของพายเป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิพายของพาย. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิพายของพายหรือแถบของพาย. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ระบุมุมของชิ้นพายหรือโดนัทชิ้นแรกเป็นองศา (ตามเข็มนาฬิกาตั้งแต่บน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิพายของพายหรือแถบของพายที่มีการแยกแบบกำหนดเอง. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุวิธีการที่ค่าขนาดบับเบิลแสดงบนแผนภูมิบับเบิล. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

ระยะของชิ้นพายที่เปิดออกจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน int.

**คืนค่า:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

ระยะของชิ้นพายที่เปิดออกจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

เป็นตัวแทนของการทำให้เส้นโค้งเรียบ. true หากเปิดการทำให้เส้นโค้งเรียบสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้เฉพาะแผนภูมิเส้นและแผนภูมิกระจายที่ต่อด้วยเส้น. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

เป็นตัวแทนของการทำให้เส้นโค้งเรียบ. true หากเปิดการทำให้เส้นโค้งเรียบสำหรับแผนภูมิเส้นหรือแผนภูมิกระจาย. ใช้ได้เฉพาะแผนภูมิเส้นและแผนภูมิกระจายที่ต่อด้วยเส้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

ส่งคืนตัวทำเครื่องหมายของซีรีส์. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของซีรีส์เปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**คืนค่า:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

ระบุรูปร่างของซีรีส์ในแผนภูมิแท่ง 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของซีรีส์เปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [ChartShapeType](../../com.aspose.slides/chartshapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

ส่งคืนชื่อซีรีส์. อ่านอย่างเดียว [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**คืนค่า:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

ส่งคืนคอลเลกชันของจุดข้อมูลของซีรีส์นี้. อ่านอย่างเดียว [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**คืนค่า:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

ส่งคืนประเภทของซีรีส์นี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**คืนค่า:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

ส่งคืนประเภทของซีรีส์นี้. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

ส่งคืนกลุ่มซีรีส์พาเรนต์. อ่านอย่างเดียว [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**คืนค่า:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ส่งคืนรูปแบบของซีรีส์. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

ส่งคืนลำดับของซีรีส์. อ่าน/เขียน int.

**คืนค่า:**  
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

ส่งคืนลำดับของซีรีส์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

ส่งคืนป้ายชื่อของซีรีส์. อ่านอย่างเดียว [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**คืนค่า:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

คอลเลกชันของเส้นแนวโน้มซีรีส์ (อ่านอย่างเดียว) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**คืนค่า:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

เป็นตัวแทนของ ErrorBars ของซีรีส์ที่มีทิศทาง X. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars ที่มีทิศทาง X มีให้ใช้สำหรับซีรีส์ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่ากำหนดเอง ให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**คืนค่า:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

เป็นตัวแทนของ ErrorBars ของซีรีส์ที่มีทิศทาง Y. อ่านอย่างเดียว [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars ที่มีทิศทาง Y มีให้ใช้สำหรับซีรีส์ประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีที่ต้องการค่ากำหนดเอง ให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**คืนค่า:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

บ่งชี้ว่าซีรีส์นี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

บ่งชี้ว่าซีรีส์นี้ถูกพล็อตบนแกนค่าที่สองหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของซีรีส์. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของซีรีส์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด X ของซีรีส์. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด X ของซีรีส์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด Y ของซีรีส์. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าพิกัด Y ของซีรีส์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของซีรีส์. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของซีรีส์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

ระบุว่าแถบ, คอลัมน์ หรือ ซีรีส์บับเบิลจะต้องกลับสีเมื่อค่าติดลบ. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

ระบุว่าแถบ, คอลัมน์ หรือ ซีรีส์บับเบิลจะต้องกลับสีเมื่อค่าติดลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

ระบุสีทึบกลับสำหรับซีรีส์. เพื่อใช้การตั้งค่าสีให้ตั้งค่า FillType ของรูปแบบซีรีส์เป็น FillType.Solid. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

เป็นตัวแทนของรายการคำอธิบายที่เกี่ยวข้องกับซีรีส์นี้ (อ่านอย่างเดียว) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
คืนค่าสีอัตโนมัติของซีรีส์โดยอิงจากดัชนีซีรีส์และสไตล์แผนภูมิ สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**
java.awt.Color - สีอัตโนมัติของซีรีส์ java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

แสดงจุดภายใน. เป็นจริงหากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

แสดงจุดภายใน. เป็นจริงหากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

แสดงจุด outlier. เป็นจริงหากจุด outlier แสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

แสดงจุด outlier. เป็นจริงหากจุด outlier แสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

แสดงเครื่องหมายค่าเฉลี่ย. เป็นจริงหากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

แสดงเครื่องหมายค่าเฉลี่ย. เป็นจริงหากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

แสดงเส้นค่าเฉลี่ย. เป็นจริงหากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

แสดงเส้นค่าเฉลี่ย. เป็นจริงหากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

ระบุวิธีการคำนวณ quartile. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น.

**คืนค่า:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

ระบุวิธีการคำนวณ quartile. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall เท่านั้น.

**คืนค่า:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

ระบุเค้าโครงของป้ายชื่อหมวดหมู่พาเรนต์. ใช้ได้เฉพาะแผนภูมิ Treemap เท่านั้น.

**คืนค่า:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

ระบุเค้าโครงของป้ายชื่อหมวดหมู่พาเรนต์. ใช้ได้เฉพาะแผนภูมิ Treemap เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

ระบุอัตราส่วนการปรับขนาดสำหรับแผนภูมิ bubble (อาจอยู่ระหว่าง 0 ถึง 300 % ของขนาดเริ่มต้น). นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.BubbleSizeScale.

**คืนค่า:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้ Property ParentSeriesGroup.UpDownBars เพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**คืนค่า:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

กำหนดระยะห่างระหว่างกลุ่มบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.GapWidth.

**คืนค่า:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

คืนค่า หรือ กำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3D. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.GapDepth.

**คืนค่า:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

ระบุว่ามาร์คเกอร์ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.IsColorVaried.

**คืนค่า:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

กำหนดว่ามีเส้นซีรีส์สำหรับซีรีส์นี้และซีรีส์ที่เกี่ยวข้องหรือไม่. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้ Property ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้นซีรีส์. อ่านอย่างเดียว boolean.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.HasSeriesLines.

**คืนค่า:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

กำหนดว่าบาร์และคอลัมน์ทับกันบนแผนภูมิ 2-D เท่าใดเป็นเปอร์เซ็นต์ (จาก -100 % ถึง 100 %). นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่. เป็นการฉายของ property ที่เหมาะสมในกลุ่มซีรีส์แม่, ดังนั้น property นี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่า, ใช้ Property ParentSeriesGroup.Overlap อ่าน/เขียน. อ่านอย่างเดียว byte.

--------------------

Overlap ระบุระดับการทับหรือช่องว่างระหว่างบาร์และคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของพวกมัน: -100 %: ช่องว่างสูงสุด (บาร์แยกจากกันทั้งหมด). 0 %: บาร์วางเคียงกันโดยไม่มีการทับหรือช่องว่าง. 100 %: การทับสูงสุด (บาร์ทับกันทั้งหมด). นี่คือการฉายของ property ParentSeriesGroup.Overlap.

**คืนค่า:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 %). นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.SecondPieSize.

**คืนค่า:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

ระบุตำแหน่งค่าที่ใช้กำหนดว่าข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับ property PieSplitBy. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว double.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.PieSplitPosition.

**คืนค่า:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

ระบุวิธีการกำหนดว่าข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) นี่คือการฉายของ property ParentSeriesGroup.PieSplitBy. 2) หากค่า property เป็น PieSplitType.Custom คุณสามารถกำหนดข้อมูลการแยกแบบกำหนดเองด้วย Property ParentSeriesGroup.PieSplitCustomPoints.

**คืนค่า:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ระบุขนาดของรูในแผนภูมิ doughnut (อาจอยู่ระหว่าง 10 ถึง 90 % ของขนาดพื้นที่ plot). นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว byte.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.DoughnutHoleSize.

**คืนค่า:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

ระบุมุมของสไลซ์แรกของแผนภูมิพายหรือ doughnut ในหน่วยองศา (นาฬิกาโดยเริ่มจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม. ดังนั้น property นี้เป็นอ่านอย่างเดียว. ใช้ Property ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้ Property ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว int.

--------------------

นี่คือการฉายของ property ParentSeriesGroup.FirstSliceAngle.

**คืนค่า:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือบาร์ที่สองของแผนภูมิ. นี่เป็น property ไม่เพียงของซีรีส์นี้แต่ของทั้งหมดในกลุ่มซีรีส์แม่ – เป็นการฉายของ property ของกลุ่มที่เหมาะสม อ่านอย่างเดียว [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

นี่คือการฉายของ property ParentSeriesGroup.PieSplitCustomPoints.

**คืนค่า:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
ระบุวิธีที่ค่าขนาดฟองแสดงบนแผนภูมิฟอง. นี่คือคุณสมบัติที่ไม่ใช่ของชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - นี่เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า.

--------------------

นี่เป็นการฉายของคุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation.

**คืนค่า:**
int