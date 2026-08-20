---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการเติมเส้นอย่างมีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/ilinefillformateffectivedata/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการเติมบรรทัดอย่างมีประสิทธิภาพ.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่าชนิดการเติม. |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีของการเติมแบบทึบ. |
| [getGradientFormat()](#getGradientFormat--) | คืนรูปแบบการเติมแบบไล่สี. |
| [getPatternFormat()](#getPatternFormat--) | คืนรูปแบบการเติมลาย. |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


คืนค่าชนิดการเติม. อ่านอย่างเดียว [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


คืนค่าสีของการเติมแบบทึบ. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


คืนรูปแบบการเติมแบบไล่สี. อ่านอย่างเดียว [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**คืนค่า:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


คืนรูปแบบการเติมลาย. อ่านอย่างเดียว [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**คืนค่า:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


กำหนดว่าการเติมควรหมุนพร้อมกับรูปร่างหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean