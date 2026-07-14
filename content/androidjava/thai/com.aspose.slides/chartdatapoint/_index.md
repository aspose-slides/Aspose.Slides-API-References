---
title: ChartDataPoint
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงจุดข้อมูลของซีรีส์.
type: docs
url: /th/com.aspose.slides/chartdatapoint/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

แสดงจุดข้อมูลของซีรีส์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าบับเบิลมีเอฟเฟกต์ 3-มิติที่ใช้กับมัน. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าบับเบิลมีเอฟเฟกต์ 3-มิติที่ใช้กับมัน. |
| [getExplosion()](#getExplosion--) | ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [getFormat()](#getFormat--) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุมาร์กเกอร์ข้อมูล. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นค่ารวม. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นค่ารวม. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | ลบ DataPoint จากซีรีส์ของแผนภูมิ. |
| [getDataPointLevels()](#getDataPointLevels--) | คืนค่าตัวเก็บระดับของจุดข้อมูล. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลจะกลับสีของมันหากค่าเป็นลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลจะกลับสีของมันหากค่าเป็นลบ. |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. อ่านอย่างเดียว [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**คืนค่า:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


คืนค่าขนาดของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Treemap และ Sunburst. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


คืนค่าชสีของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Map. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Represents series error bars values in case of Custom value type. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**คืนค่า:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


ระบุว่าบับเบิลมีเอฟเฟกต์ 3-มิติที่ใช้กับมัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


ระบุว่าบับเบิลมีเอฟเฟกต์ 3-มิติที่ใช้กับมัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**คืนค่า:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


ระบุมาร์กเกอร์ข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


ตั้งค่าจุดข้อมูลเป็นค่ารวม. ใช้สำหรับประเภทซีรีส์ Waterfall เท่านั้น.

**คืนค่า:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


ตั้งค่าจุดข้อมูลเป็นค่ารวม. ใช้สำหรับประเภทซีรีส์ Waterfall เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


ลบ DataPoint จากซีรีส์ของแผนภูมิ.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


คืนค่าตัวเก็บระดับของจุดข้อมูล. ใช้กับซีรีส์ Treeamp และ Sunburst. การจัดลำดับของระดับจุดข้อมูลเริ่มจากศูนย์.

**คืนค่า:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**คืนค่า:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```


คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอ้างอิงจากดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์ของแผนภูมิ. สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


ระบุว่าจุดข้อมูลจะกลับสีของมันหากค่าเป็นลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


ระบุว่าจุดข้อมูลจะกลับสีของมันหากค่าเป็นลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float