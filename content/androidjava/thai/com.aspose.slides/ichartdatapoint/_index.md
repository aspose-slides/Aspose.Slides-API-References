---
title: IChartDataPoint
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของจุดข้อมูลซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartdatapoint/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

เป็นตัวแทนของจุดข้อมูลซีรีส์.
## เมธอด

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | คืนค่าค่า x ของจุดข้อมูลแผนภูมิ. |
| [getYValue()](#getYValue--) | คืนค่าค่า y ของจุดข้อมูลแผนภูมิ. |
| [getBubbleSize()](#getBubbleSize--) | คืนค่าขนาดฟองของจุดข้อมูลแผนภูมิ. |
| [getValue()](#getValue--) | คืนค่าของจุดข้อมูลแผนภูมิ. |
| [getSizeValue()](#getSizeValue--) | คืนค่าขนาดของจุดข้อมูลแผนภูมิ. |
| [getColorValue()](#getColorValue--) | คืนค่าสีของจุดข้อมูลแผนภูมิ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | เป็นตัวแทนของค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีที่เป็นประเภทค่าที่กำหนดเอง. |
| [getLabel()](#getLabel--) | เป็นตัวแทนของป้ายของจุดข้อมูลแผนภูมิ. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [getExplosion()](#getExplosion--) | ระบุปริมาณที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุปริมาณที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [getFormat()](#getFormat--) | เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุเครื่องหมายข้อมูล. |
| [remove()](#remove--) | ลบ DataPoint จากซีรีส์แผนภูมิ. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิอยู่ในรายการนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นทั้งหมด. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นทั้งหมด. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลจะย้อนสีของมันหากค่ามีค่าเป็นลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลจะย้อนสีของมันหากค่ามีค่าเป็นลบ. |
| [getDataPointLevels()](#getDataPointLevels--) | คืนค่าคอนเทนเนอร์ของระดับจุดข้อมูล. |
| [getIndex()](#getIndex--) | กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันของลูกของพาเรนท์ใด. |

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

คืนค่าสีของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิแผนที่. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

เป็นตัวแทนของค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีที่เป็นประเภทค่าที่กำหนดเอง. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**คืนค่า:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

เป็นตัวแทนของป้ายของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

ระบุปริมาณที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**คืนค่า:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

ระบุปริมาณที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

ระบุเครื่องหมายข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

ลบ DataPoint จากซีรีส์แผนภูมิ.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType มีค่าเท่ากับ NotDefined.

**คืนค่า:**
java.lang.Integer - สีอัตโนมัติของจุดข้อมูล java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิอยู่ในรายการนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

ตั้งค่าจุดข้อมูลเป็นทั้งหมด. ใช้สำหรับประเภทซีรีส์ Waterfall เท่านั้น.

**คืนค่า:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

ตั้งค่าจุดข้อมูลเป็นทั้งหมด. ใช้สำหรับประเภทซีรีส์ Waterfall เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

ระบุว่าจุดข้อมูลจะย้อนสีของมันหากค่ามีค่าเป็นลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

ระบุว่าจุดข้อมูลจะย้อนสีของมันหากค่ามีค่าเป็นลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

คืนค่าคอนเทนเนอร์ของระดับจุดข้อมูล. ใช้กับซีรีส์ Treeamp และ Sunburst. การจัดทำดัชนีระดับจุดข้อมูลเริ่มต้นจากศูนย์.

**คืนค่า:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันของลูกของพาเรนท์ใด. อ่าน long.

**คืนค่า:**
long