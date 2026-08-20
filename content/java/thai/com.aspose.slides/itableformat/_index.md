---
title: ITableFormat
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงรูปแบบของตาราง.
type: docs
url: /th/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

แสดงรูปแบบของตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | คืนค่าอ็อบเจ็กต์คุณสมบัติกรอกระดาษของตาราง. |
| [getTransparency()](#getTransparency--) | รับหรือกำหนดค่าความโปร่งใสของสีเติม. |
| [setTransparency(float value)](#setTransparency-float-) | รับหรือกำหนดค่าความโปร่งใสของสีเติม. |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบตารางที่มีผลรวมกับการสืบทอดและสไตล์ตารางที่นำไปใช้. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่าอ็อบเจ็กต์คุณสมบัติกรอกระดาษของตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

รับหรือกำหนดค่าความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**คืนค่า:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

รับหรือกำหนดค่าความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

รับคุณสมบัติการจัดรูปแบบตารางที่มีผลรวมกับการสืบทอดและสไตล์ตารางที่นำไปใช้.

**คืนค่า:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - หนึ่ง [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).