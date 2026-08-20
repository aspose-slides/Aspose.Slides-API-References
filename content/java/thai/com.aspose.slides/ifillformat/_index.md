---
title: IFillFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกการจัดรูปแบบการเติมสี.
type: docs
url: /th/com.aspose.slides/ifillformat/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

แสดงตัวเลือกการจัดรูปแบบการเติมสี.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่า หรือกำหนดประเภทการเติมสี. |
| [setFillType(byte value)](#setFillType-byte-) | คืนค่า หรือกำหนดประเภทการเติมสี. |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีการเติม |
| [getGradientFormat()](#getGradientFormat--) | คืนค่ารูปแบบการเติมแบบไล่ระดับสี |
| [getPatternFormat()](#getPatternFormat--) | คืนค่ารูปแบบการเติมแบบลาย |
| [getPictureFillFormat()](#getPictureFillFormat--) | คืนค่ารูปแบบการเติมภาพ |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบการเติมที่มีผลโดยใช้การสืบทอด |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

คืนค่า หรือกำหนดประเภทการเติมสี. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

คืนค่า หรือกำหนดประเภทการเติมสี. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

คืนค่าสีการเติม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

คืนค่ารูปแบบการเติมแบบไล่ระดับสี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**คืนค่า:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

คืนค่ารูปแบบการเติมแบบลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**คืนค่า:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

คืนค่ารูปแบบการเติมภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบการเติมที่มีผลโดยใช้การสืบทอด

**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - เป็น [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).