---
title: LineFillFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคุณสมบัติสำหรับการเติมเส้น.
type: docs
url: /th/com.aspose.slides/linefillformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

แสดงคุณสมบัติสำหรับการเติมเส้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | คืนค่า หรือ ตั้งค่าชนิดการเติม |
| [setFillType(byte value)](#setFillType-byte-) | คืนค่า หรือ ตั้งค่าชนิดการเติม |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีของการเติมแบบทึบ |
| [getGradientFormat()](#getGradientFormat--) | คืนรูปแบบการเติมแบบไล่สี |
| [getPatternFormat()](#getPatternFormat--) | คืนรูปแบบการเติมแบบลาย |
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


คืนค่า หรือ ตั้งค่าชนิดการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


คืนค่า หรือ ตั้งค่าชนิดการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


คืนค่าสีของการเติมแบบทึบ. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


คืนรูปแบบการเติมแบบไล่สี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**คืนค่า:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


คืนรูปแบบการเติมแบบลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**คืนค่า:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)