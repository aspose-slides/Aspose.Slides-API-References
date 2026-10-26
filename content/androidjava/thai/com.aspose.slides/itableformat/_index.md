---
title: ITableFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
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
| [getFillFormat()](#getFillFormat--) | ส่งคืนอ็อบเจกต์คุณสมบัติการเติมของตาราง. |
| [getTransparency()](#getTransparency--) | รับหรือกำหนดค่าความโปร่งแสงของสีการเติม. |
| [setTransparency(float value)](#setTransparency-float-) | รับหรือกำหนดค่าความโปร่งแสงของสีการเติม. |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบตารางที่มีผลโดยมีการสืบทอดและสไตล์ตารางที่ใช้. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


ส่งคืนอ็อบเจกต์คุณสมบัติการเติมของตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**ส่งคืน:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


รับหรือกำหนดค่าความโปร่งแสงของสีการเติม. อ่าน/เขียน  float .

**ส่งคืน:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


รับหรือกำหนดค่าความโปร่งแสงของสีการเติม. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


รับคุณสมบัติการจัดรูปแบบตารางที่มีผลโดยมีการสืบทอดและสไตล์ตารางที่ใช้.

**ส่งคืน:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).