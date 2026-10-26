---
title: ILineFillFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติสำหรับการเติมเส้น.
type: docs
url: /th/com.aspose.slides/ilinefillformat/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

แสดงคุณสมบัติสำหรับการเติมเส้น
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่า หรือ ตั้งค่า ประเภทการเติม |
| [setFillType(byte value)](#setFillType-byte-) | คืนค่า หรือ ตั้งค่า ประเภทการเติม |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีของการเติมแบบทึบ |
| [getGradientFormat()](#getGradientFormat--) | คืนรูปแบบการเติมแบบไล่ระดับสี |
| [getPatternFormat()](#getPatternFormat--) | คืนรูปแบบการเติมแบบลวดลาย |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่ |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่ |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

คืนค่า หรือ ตั้งค่า ประเภทการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

คืนค่า หรือ ตั้งค่า ประเภทการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

คืนค่าสีของการเติมแบบทึบ. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

คืนรูปแบบการเติมแบบไล่ระดับสี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**คืนค่า:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

คืนรูปแบบการเติมแบบลวดลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**คืนค่า:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |