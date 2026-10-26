---
title: FillFormat
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงตัวเลือกการจัดรูปแบบการเติม.
type: docs
url: /th/com.aspose.slides/fillformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทั้งหมดของอินเทอร์เฟซที่ใช้งาน:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

แสดงตัวเลือกการจัดรูปแบบการเติม.
## วิธีการ

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | ส่งคืนหรือกำหนดประเภทของการเติม. |
| [setFillType(byte value)](#setFillType-byte-) | ส่งคืนหรือกำหนดประเภทของการเติม. |
| [getSolidFillColor()](#getSolidFillColor--) | ส่งคืนสีการเติม. |
| [getGradientFormat()](#getGradientFormat--) | ส่งคืนรูปแบบการเติมแบบไล่ระดับสี. |
| [getPatternFormat()](#getPatternFormat--) | ส่งคืนรูปแบบการเติมลาย. |
| [getPictureFillFormat()](#getPictureFillFormat--) | ส่งคืนรูปแบบการเติมรูปภาพ. |
| [getRotateWithShape()](#getRotateWithShape--) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบการเติมที่มีผลโดยมีการสืบทอด. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**ส่งคืน:**
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

ส่งคืนหรือกำหนดประเภทของการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**ส่งคืน:**
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

ส่งคืนหรือกำหนดประเภทของการเติม. อ่าน/เขียน [FillType](../../com.aspose.slides/filltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

ส่งคืนสีการเติม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

ส่งคืนรูปแบบการเติมแบบไล่ระดับสี. อ่านอย่างเดียว [IGradientFormat](../../com.aspose.slides/igradientformat).

**ส่งคืน:**
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

ส่งคืนรูปแบบการเติมลาย. อ่านอย่างเดียว [IPatternFormat](../../com.aspose.slides/ipatternformat).

**ส่งคืน:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

ส่งคืนรูปแบบการเติมรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**ส่งคืน:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ส่งคืน:**
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

กำหนดว่าการเติมควรหมุนตามรูปร่างหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบการเติมที่มีผลโดยมีการสืบทอด.

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


**ส่งคืน:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - หนึ่ง [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).