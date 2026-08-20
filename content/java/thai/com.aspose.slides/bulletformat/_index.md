---
title: BulletFormat
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงคุณสมบัติการจัดรูปแบบหัวกระดาษของย่อหน้า.
type: docs
url: /th/com.aspose.slides/bulletformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Represents paragraph bullet formatting properties.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | คืนค่า หรือ ตั้งค่าชนิดของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [setType(byte value)](#setType-byte-) | คืนค่า หรือ ตั้งค่าชนิดของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [getChar()](#getChar--) | คืนค่า หรือ ตั้งค่าตัวอักษรหัวกระดาษของย่อหน้าที่ไม่มีการสืบทอด. |
| [setChar(char value)](#setChar-char-) | คืนค่า หรือ ตั้งค่าตัวอักษรหัวกระดาษของย่อหน้าที่ไม่มีการสืบทอด. |
| [getFont()](#getFont--) | คืนค่า หรือ ตั้งค่าแบบอักษรของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | คืนค่า หรือ ตั้งค่าแบบอักษรของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [getHeight()](#getHeight--) | คืนค่า หรือ ตั้งค่าสูงของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [setHeight(float value)](#setHeight-float-) | คืนค่า หรือ ตั้งค่าสูงของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [getColor()](#getColor--) | คืนรูปแบบสีของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวกระดาษลำดับเลขในย่อหน้าที่ไม่มีการสืบทอด. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวกระดาษลำดับเลขในย่อหน้าที่ไม่มีการสืบทอด. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | คืนค่า หรือ ตั้งค่าสไตล์ของหัวกระดาษลำดับเลขที่ไม่มีการสืบทอด. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | คืนค่า หรือ ตั้งค่าสไตล์ของหัวกระดาษลำดับเลขที่ไม่มีการสืบทอด. |
| [isBulletHardColor()](#isBulletHardColor--) | กำหนดว่าหัวกระดาษมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | กำหนดว่าหัวกระดาษมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [isBulletHardFont()](#isBulletHardFont--) | กำหนดว่าหัวกระดาษมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | กำหนดว่าหัวกระดาษมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [getPicture()](#getPicture--) | คืนรูปภาพที่ใช้เป็นหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | ตั้งค่าการยกเลื่อนเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้หัวกระดาษ (เช่น PowerPoint ทำเมื่อเปิดใช้งานหัวกระดาษ/การจัดลำดับเลขในย่อหน้า). |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบหัวกระดาษที่มีผลพร้อมการสืบทอดที่ใช้. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

คืนค่า หรือ ตั้งค่าชนิดของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**คืนค่า:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

คืนค่า หรือ ตั้งค่าชนิดของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

คืนค่า หรือ ตั้งค่าตัวอักษรหัวกระดาษของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  char .

**คืนค่า:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

คืนค่า หรือ ตั้งค่าตัวอักษรหัวกระดาษของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  char .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

คืนค่า หรือ ตั้งค่าแบบอักษรของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

คืนค่า หรือ ตั้งค่าแบบอักษรของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

คืนค่า หรือ ตั้งค่าสูงของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดให้หัวกระดาษสืบทอดความสูงจากส่วนแรกของย่อหน้า. อ่าน/เขียน  float .

--------------------

ค่าความสูงเป็นค่าลบหมายถึงความสูงกำหนดเป็นจุดและค่าบวกหมายถึงความสูงเป็นเปอร์เซ็นต์ของข้อความรอบข้าง.

**คืนค่า:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

คืนค่า หรือ ตั้งค่าสูงของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดให้หัวกระดาษสืบทอดความสูงจากส่วนแรกของย่อหน้า. อ่าน/เขียน  float .

--------------------

ค่าความสูงเป็นค่าลบหมายถึงความสูงกำหนดเป็นจุดและค่าบวกหมายถึงความสูงเป็นเปอร์เซ็นต์ของข้อความรอบข้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

คืนรูปแบบสีของหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวกระดาษลำดับเลขในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  short .

**คืนค่า:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวกระดาษลำดับเลขในย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  short .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

คืนค่า หรือ ตั้งค่าสไตล์ของหัวกระดาษลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**คืนค่า:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

คืนค่า หรือ ตั้งค่าสไตล์ของหัวกระดาษลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

กำหนดว่าหัวกระดาษมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool.True** หากหัวกระดาษมีสีของตนเองและ **NullableBool.False** หากหัวกระดาษสืบทอดสีจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

กำหนดว่าหัวกระดาษมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool.True** หากหัวกระดาษมีสีของตนเองและ **NullableBool.False** หากหัวกระดาษสืบทอดสีจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

กำหนดว่าหัวกระดาษมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool.True** หากหัวกระดาษมีแบบอักษรของตนเองและ **NullableBool.False** หากหัวกระดาษสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

กำหนดว่าหัวกระดาษมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool.True** หากหัวกระดาษมีแบบอักษรของตนเองและ **NullableBool.False** หากหัวกระดาษสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

คืนรูปภาพที่ใช้เป็นหัวกระดาษในย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [ISlidesPicture](../../com.aspose.slides/islidespicture).

**คืนค่า:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

ตั้งค่าการยกเลื่อนเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้หัวกระดาษ (เช่น PowerPoint ทำเมื่อเปิดใช้งานหัวกระดาษ/การจัดลำดับเลขในย่อหน้า). หากปิดใช้งานหัวกระดาษก็จะรีเซ็ตค่า Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดการใช้งานหัวกระดาษ/การจัดลำดับเลขในย่อหน้า). การยกเลื่อนจะถูกนำไปใช้โดยอ้างอิงกับบริบทของหัวกระดาษปัจจุบัน - IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การยกเลื่อนที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบหัวกระดาษที่มีผลพร้อมการสืบทอดที่ใช้.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long