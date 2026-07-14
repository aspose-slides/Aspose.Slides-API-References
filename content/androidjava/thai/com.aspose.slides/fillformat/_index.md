---
title: FillFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวเลือกการจัดรูปแบบการเติมสี.
type: docs
url: /th/com.aspose.slides/fillformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

เป็นตัวเลือกการจัดรูปแบบการเติมสี.
## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | คืนค่า หรือกำหนดประเภทการเติมสี. |
| [setFillType(byte value)](#setFillType-byte-) | คืนค่า หรือกำหนดประเภทการเติมสี. |
| [getSolidFillColor()](#getSolidFillColor--) | คืนค่าสีการเติม. |
| [getGradientFormat()](#getGradientFormat--) | คืนรูปแบบการเติมสีแบบไล่ระดับ. |
| [getPatternFormat()](#getPatternFormat--) | คืนรูปแบบการเติมสีแบบลาย. |
| [getPictureFillFormat()](#getPictureFillFormat--) | คืนรูปแบบการเติมสีด้วยรูปภาพ. |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมสีควรหมุนตามรูปร่างหรือไม่. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมสีควรหมุนตามรูปร่างหรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบการเติมสีที่ใช้การสืบทอดแล้ว. |
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


คืนค่า หรือกำหนดประเภทการเติมสี. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**คืนค่า:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


คืนค่า หรือกำหนดประเภทการเติมสี. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


คืนค่าสีการเติม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


คืนรูปแบบการเติมสีแบบไล่ระดับ. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**คืนค่า:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


คืนรูปแบบการเติมสีแบบลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**คืนค่า:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


คืนรูปแบบการเติมสีด้วยรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


กำหนดว่าการเติมสีควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


กำหนดว่าการเติมสีควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


รับข้อมูลการจัดรูปแบบการเติมสีที่ใช้การสืบทอดแล้ว.

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - หนึ่ง [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).