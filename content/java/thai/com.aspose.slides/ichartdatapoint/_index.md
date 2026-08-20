---
title: IChartDataPoint
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: แสดงจุดข้อมูลของชุดซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Represents series data point.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXValue()](#getXValue--) | คืนค่าค่า x ของจุดข้อมูลแผนภูมิ. |
| [getYValue()](#getYValue--) | คืนค่าค่า y ของจุดข้อมูลแผนภูมิ. |
| [getBubbleSize()](#getBubbleSize--) | คืนค่าขนาดฟองของจุดข้อมูลแผนภูมิ. |
| [getValue()](#getValue--) | คืนค่าของจุดข้อมูลแผนภูมิ. |
| [getSizeValue()](#getSizeValue--) | คืนค่าขนาดของจุดข้อมูลแผนภูมิ. |
| [getColorValue()](#getColorValue--) | คืนค่าสีของจุดข้อมูลแผนภูมิ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | แสดงค่าขอบความผิดพลาดของชุดข้อมูลในกรณีประเภทค่าแบบกำหนดเอง. |
| [getLabel()](#getLabel--) | แสดงป้ายชื่อของจุดข้อมูลแผนภูมิ. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ถูกใช้กับพวกมัน. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ถูกใช้กับพวกมัน. |
| [getExplosion()](#getExplosion--) | ระบุจำนวนที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุจำนวนที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของพาย. |
| [getFormat()](#getFormat--) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุมาร์คเกอร์ข้อมูล. |
| [remove()](#remove--) | ลบ DataPoint ออกจากชุดข้อมูลแผนภูมิ. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีชุดข้อมูล ดัชนีจุดข้อมูล คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องในกรณีประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลควรกลับสีหากค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลควรกลับสีหากค่าติดลบ. |
| [getDataPointLevels()](#getDataPointLevels--) | คืนค่าตัวคอนเทนเนอร์ของระดับจุดข้อมูล. |
| [getIndex()](#getIndex--) | กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันลูกของผู้ปกครองใด. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

คืนค่าค่า x ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**คืนค่า:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

คืนค่าค่า y ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

คืนค่าขนาดฟองของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

คืนค่าของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

คืนค่าขนาดของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Treemap และ Sunburst. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

คืนค่าสีของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Map. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

แสดงค่าขอบความผิดพลาดของชุดข้อมูลในกรณีประเภทค่าแบบกำหนดเอง. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**คืนค่า:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

แสดงป้ายชื่อของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ถูกใช้กับพวกมัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ถูกใช้กับพวกมัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

ระบุจำนวนที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**คืนค่า:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

ระบุจำนวนที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

ระบุมาร์คเกอร์ข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

ลบ DataPoint ออกจากชุดข้อมูลแผนภูมิ.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีชุดข้อมูล ดัชนีจุดข้อมูล คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType มีค่าเท่ากับ NotDefined.

**คืนค่า:**
java.awt.Color - สีอัตโนมัติของจุดข้อมูล java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

คุณสมบัติของรายการคำอธิบายที่สอดคล้องในกรณีประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้กับประเภทชุดข้อมูล Waterfall เท่านั้น.

**คืนค่า:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้กับประเภทชุดข้อมูล Waterfall เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

ระบุว่าจุดข้อมูลควรกลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

ระบุว่าจุดข้อมูลควรกลับสีหากค่าติดลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

คืนค่าตัวคอนเทนเนอร์ของระดับจุดข้อมูล. ใช้กับชุดข้อมูล Treeamp และ Sunburst. การจัดอันดับระดับจุดข้อมูลเริ่มจากศูนย์.

**คืนค่า:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันลูกของผู้ปกครองใด. อ่าน long.

**คืนค่า:**
long