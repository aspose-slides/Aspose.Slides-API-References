---
title: IFillFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ออบเจ็กต์ไม่เปลี่ยนแปลงที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีที่มีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/ifillformateffectivedata/
---
**ทั้งหมดที่ใช้งานอินเทอร์เฟซ:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

ออบเจ็กต์ไม่เปลี่ยนแปลงที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IFillFormat](../../com.aspose.slides/ifillformat) เพื่อคืนค่าการจัดรูปแบบที่มีประสิทธิภาพโดยมีการสืบทอดที่นำไปใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillType()](#getFillType--) | คืนค่าประเภทการเติมสี |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีเติม |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | รับค่าสีเติมที่กำหนดโดยชุดสี |
| [getGradientFormat()](#getGradientFormat--) | คืนค่ารูปแบบการเติมสีแบบไล่สี |
| [getPatternFormat()](#getPatternFormat--) | คืนค่ารูปแบบการเติมสีแบบลวดลาย |
| [getPictureFillFormat()](#getPictureFillFormat--) | คืนค่ารูปแบบการเติมสีรูปภาพ |
| [getRotateWithShape()](#getRotateWithShape--) | ระบุว่าจะให้การเติมสีหมุนตามรูปร่างหรือไม่ |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


คืนค่าประเภทการเติมสี อ่านอย่างเดียว [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


คืนค่าสีเติม อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


รับค่าสีเติมที่กำหนดโดยชุดสี ค่า [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) แสดงว่า SolidFillColor (\#getSolidFillColor.getSolidFillColor) ไม่ใช่สีจากชุดสี อ่านอย่างเดียว [SchemeColor](../../com.aspose.slides/schemecolor).

**คืนค่า:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


คืนค่ารูปแบบการเติมสีแบบไล่สี อ่านอย่างเดียว [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**คืนค่า:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


คืนค่ารูปแบบการเติมสีแบบลวดลาย อ่านอย่างเดียว [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**คืนค่า:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


คืนค่ารูปแบบการเติมสีรูปภาพ อ่านอย่างเดียว [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**คืนค่า:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


ระบุว่าจะให้การเติมสีหมุนตามรูปร่างหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean