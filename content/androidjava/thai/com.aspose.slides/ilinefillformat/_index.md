---
title: ILineFillFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคุณสมบัติสำหรับการเติมเส้น.
type: docs
url: /th/com.aspose.slides/ilinefillformat/
---
**อินเทอร์เฟซที่ใช้ทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

เป็นการแสดงคุณสมบัติสำหรับการเติมเส้น
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | ส่งคืนหรือกำหนดประเภทการเติม |
| [setFillType(byte value)](#setFillType-byte-) | ส่งคืนหรือกำหนดประเภทการเติม |
| [getSolidFillColor()](#getSolidFillColor--) | ส่งคืนสีของการเติมแบบทึบ |
| [getGradientFormat()](#getGradientFormat--) | ส่งคืนรูปแบบการเติมแบบไล่ระดับสี |
| [getPatternFormat()](#getPatternFormat--) | ส่งคืนรูปแบบการเติมแบบลวดลาย |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่ |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


ส่งคืนหรือกำหนดประเภทการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**ส่งคืน:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


ส่งคืนหรือกำหนดประเภทการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


ส่งคืนสีของการเติมแบบทึบ. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


ส่งคืนรูปแบบการเติมแบบไล่ระดับสี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**ส่งคืน:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


ส่งคืนรูปแบบการเติมแบบลวดลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**ส่งคืน:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ส่งคืน:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |