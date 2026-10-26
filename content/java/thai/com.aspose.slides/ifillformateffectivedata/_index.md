---
title: IFillFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งบรรจุคุณสมบัติการจัดรูปแบบการเติมที่มีผล
type: docs
url: /th/com.aspose.slides/ifillformateffectivedata/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบการเติมที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IFillFormat](../../com.aspose.slides/ifillformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยใช้การสืบทอด

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Gets the fill color defined by a color scheme. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

คืนค่าชนิดของการเติม. อ่านอย่างเดียว [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

คืนค่าสีการเติม. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color

### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

รับสีการเติมที่กำหนดโดยโครงร่างสี. ค่าที่ [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) ระบุว่า SolidFillColor (\#getSolidFillColor.getSolidFillColor) ไม่ใช่สีจากโครงร่าง. อ่านอย่างเดียว [SchemeColor](../../com.aspose.slides/schemecolor).

**คืนค่า:**
int

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

คืนรูปแบบการเติมแบบลวดลาย. อ่านอย่างเดียว [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**คืนค่า:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

คืนรูปแบบการเติมแบบรูปภาพ. อ่านอย่างเดียว [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**คืนค่า:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

กำหนดว่าการเติมจะหมุนตามรูปร่างหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean