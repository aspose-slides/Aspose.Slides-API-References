---
title: IFillFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวเลือกการจัดรูปแบบการเติม.
type: docs
url: /th/com.aspose.slides/ifillformat/
---
**ส่วนติดต่อที่ใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Represents a fill formatting options.
## เมธอด

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่า หรือกำหนดประเภทของการเติม. |
| [setFillType(byte value)](#setFillType-byte-) | คืนค่า หรือกำหนดประเภทของการเติม. |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีเติม. |
| [getGradientFormat()](#getGradientFormat--) | คืนรูปแบบการไล่สี. |
| [getPatternFormat()](#getPatternFormat--) | คืนรูปแบบลวดลาย. |
| [getPictureFillFormat()](#getPictureFillFormat--) | คืนรูปแบบรูปภาพ. |
| [getRotateWithShape()](#getRotateWithShape--) | ระบุว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | ระบุว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบเติมที่มีผลพร้อมกับการสืบทอดที่ใช้. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

คืนค่า หรือกำหนดประเภทของการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

คืนค่า หรือกำหนดประเภทของการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

คืนค่าสีเติม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

คืนรูปแบบการไล่สี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**คืนค่า:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

คืนรูปแบบลวดลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**คืนค่า:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

คืนรูปแบบรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

ระบุว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

ระบุว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบเติมที่มีผลพร้อมกับการสืบทอดที่ใช้.

**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - เป็น [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).