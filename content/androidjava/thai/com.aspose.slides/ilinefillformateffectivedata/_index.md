---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการเติมเส้นที่มีประสิทธิภาพ
type: docs
url: /th/com.aspose.slides/ilinefillformateffectivedata/
---
**ส่วนต่อประสานทั้งหมดที่นำไปใช้:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการเติมเส้นที่มีประสิทธิภาพ

--------------------

ส่วนต่อประสานนี้ถูกใช้เป็นส่วนหนึ่งของ [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่าประเภทการเติม. |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีของการเติมแบบทึบ. |
| [getGradientFormat()](#getGradientFormat--) | คืนค่ารูปแบบการเติมแบบไล่ระดับสี. |
| [getPatternFormat()](#getPatternFormat--) | คืนค่ารูปแบบการเติมแบบลาย. |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรถูกหมุนตามรูปหรือไม่. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


คืนค่าประเภทการเติม. อ่านอย่างเดียว [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


คืนค่าสีของการเติมแบบทึบ. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


คืนค่ารูปแบบการเติมแบบไล่ระดับสี. อ่านอย่างเดียว [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**คืนค่า:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


คืนค่ารูปแบบการเติมแบบลาย. อ่านอย่างเดียว [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**คืนค่า:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


กำหนดว่าการเติมควรถูกหมุนตามรูปหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean