---
title: ChartDataPoint
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของจุดข้อมูลซีรีส์
type: docs
url: /th/com.aspose.slides/chartdatapoint/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

แสดงจุดข้อมูลซีรีส์.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | คืนค่าขนาดของจุดข้อมูลแผนภูมิ. |
| [getColorValue()](#getColorValue--) | คืนค่าสีของจุดข้อมูลแผนภูมิ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | แสดงค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีประเภทค่าแบบ Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าฟองอากาศมีเอฟเฟกต์ 3 มิติที่ถูกใช้. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าฟองอากาศมีเอฟเฟกต์ 3 มิติที่ถูกใช้. |
| [getExplosion()](#getExplosion--) | ระบุปริมาณที่จุดข้อมูลจะถูกเลื่อนออกจากศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุปริมาณที่จุดข้อมูลจะถูกเลื่อนออกจากศูนย์กลางของพาย. |
| [getFormat()](#getFormat--) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุตัวทำเครื่องหมายข้อมูล. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นผลรวม. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นผลรวม. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิเป็นหนึ่งในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | ลบ DataPoint จากชุดข้อมูลแผนภูมิ. |
| [getDataPointLevels()](#getDataPointLevels--) | คืนค่าที่เก็บระดับจุดข้อมูล. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | คืนค่าสีอัตโนมัติของจุดข้อมูลตามลำดับซีรีส์, ลำดับจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ. |
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

คืนค่าขนาดของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Treemap และ Sunburst. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

คืนค่าสีของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Map. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

แสดงค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีประเภทค่าแบบ Custom. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

ระบุว่าฟองอากาศมีเอฟเฟกต์ 3 มิติที่ถูกใช้. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

ระบุว่าฟองอากาศมีเอฟเฟกต์ 3 มิติที่ถูกใช้. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

ระบุปริมาณที่จุดข้อมูลจะถูกเลื่อนออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**คืนค่า:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

ระบุปริมาณที่จุดข้อมูลจะถูกเลื่อนออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**พารามิเตอร์:**  
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

ระบุตัวทำเครื่องหมายข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**  
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

ตั้งค่าจุดข้อมูลเป็นผลรวม. ใช้สำหรับชนิดซีรีส์ Waterfall เท่านั้น.

**คืนค่า:**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

ตั้งค่าจุดข้อมูลเป็นผลรวม. ใช้สำหรับชนิดซีรีส์ Waterfall เท่านั้น.

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิเป็นหนึ่งในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

ลบ DataPoint จากชุดข้อมูลแผนภูมิ.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

คืนค่าที่เก็บระดับจุดข้อมูล. ใช้สำหรับซีรีส์ Treeamp และ Sunburst. การนับระดับจุดข้อมูลเป็นศูนย์ฐาน.

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

คืนค่าออบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

คืนค่าสีอัตโนมัติของจุดข้อมูลตามลำดับซีรีส์, ลำดับจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. สีนี้จะถูกใช้โดยค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**  
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| Parameter | Type | Description |
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