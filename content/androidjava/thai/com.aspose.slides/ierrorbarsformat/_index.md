---
title: IErrorBarsFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงแถบความคลาดเคลื่อนของชุดข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | รับหรือกำหนดประเภทของแถบความคลาดเคลื่อน. |
| [setType(int value)](#setType-int-) | รับหรือกำหนดประเภทของแถบความคลาดเคลื่อน. |
| [getValueType()](#getValueType--) | แสดงวิธีการที่เป็นไปได้ในการกำหนดความยาวของแถบความคลาดเคลื่อน. |
| [setValueType(int value)](#setValueType-int-) | แสดงวิธีการที่เป็นไปได้ในการกำหนดความยาวของแถบความคลาดเคลื่อน. |
| [hasEndCap()](#hasEndCap--) | ระบุว่าไม่วาดหัวปลายบนแถบความคลาดเคลื่อน. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | ระบุว่าไม่วาดหัวปลายบนแถบความคลาดเคลื่อน. |
| [getValue()](#getValue--) | รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบความคลาดเคลื่อน. |
| [setValue(float value)](#setValue-float-) | รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบความคลาดเคลื่อน. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของแถบความคลาดเคลื่อน. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของแถบความคลาดเคลื่อน. |
| [isVisible()](#isVisible--) | รับหรือกำหนดการมองเห็นของ Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | รับหรือกำหนดการมองเห็นของ Error Bars. |
### getType() {#getType--}
```
public abstract int getType()
```

รับหรือกำหนดประเภทของแถบความคลาดเคลื่อน. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

รับหรือกำหนดประเภทของแถบความคลาดเคลื่อน. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

แสดงวิธีการที่เป็นไปได้ในการกำหนดความยาวของแถบความคลาดเคลื่อน. ในกรณีประเภทค่าที่กำหนดเองเพื่อระบุค่าใช้คุณสมบัติ [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**คืนค่า:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

แสดงวิธีการที่เป็นไปได้ในการกำหนดความยาวของแถบความคลาดเคลื่อน. ในกรณีประเภทค่าที่กำหนดเองเพื่อระบุค่าใช้คุณสมบัติ [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

ระบุว่าไม่วาดหัวปลายบนแถบความคลาดเคลื่อน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

ระบุว่าไม่วาดหัวปลายบนแถบความคลาดเคลื่อน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบความคลาดเคลื่อน. อ่าน/เขียน float.

**คืนค่า:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบความคลาดเคลื่อน. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

แสดงรูปแบบของแถบความคลาดเคลื่อน. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

แสดงรูปแบบของแถบความคลาดเคลื่อน. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |