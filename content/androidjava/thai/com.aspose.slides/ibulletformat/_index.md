---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้า.
type: docs
url: /th/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

แสดงคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้า.

## เมธอด

| Method | Description |
| --- | --- |
| [getType()](#getType--) | คืนค่า หรือ ตั้งค่าชนิดหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [setType(byte value)](#setType-byte-) | คืนค่า หรือ ตั้งค่าชนิดหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [getChar()](#getChar--) | คืนค่า หรือ ตั้งค่าตัวอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [setChar(char value)](#setChar-char-) | คืนค่า หรือ ตั้งค่าตัวอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [getFont()](#getFont--) | คืนค่า หรือ ตั้งค่าแบบอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | คืนค่า หรือ ตั้งค่าแบบอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [getHeight()](#getHeight--) | คืนค่า หรือ ตั้งค่าความสูงของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [setHeight(float value)](#setHeight-float-) | คืนค่า หรือ ตั้งค่าความสูงของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [getColor()](#getColor--) | คืนค่ารูปแบบสีของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. |
| [getPicture()](#getPicture--) | คืนค่าภาพที่ใช้เป็นหัวข้อย่อยในย่อหน้าที่ไม่มีการสืบทอด. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | คืนค่า หรือ ตั้งค่าสไตล์ของหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | คืนค่า หรือ ตั้งค่าสไตล์ของหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. |
| [isBulletHardColor()](#isBulletHardColor--) | กำหนดว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | กำหนดว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [isBulletHardFont()](#isBulletHardFont--) | กำหนดว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | กำหนดว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | ตั้งค่าการยืดอิเล็กต์เริ่มต้นที่ไม่เป็นศูนย์สำหรับการเยื้องและ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้หัวข้อย่อย (เช่น PowerPoint ทำเมื่อเปิดใช้งานหัวข้อย่อย/การนับลำดับในย่อหน้า). |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบหัวข้อย่อยที่มีผลพร้อมการสืบทอดที่ใช้. |

### getType() {#getType--}
```
public abstract byte getType()
```

คืนค่า หรือ ตั้งค่าชนิดหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**คืนค่า:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

คืนค่า หรือ ตั้งค่าชนิดหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

คืนค่า หรือ ตั้งค่าตัวอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน char.

**คืนค่า:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

คืนค่า หรือ ตั้งค่าตัวอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน char.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

คืนค่า หรือ ตั้งค่าแบบอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

คืนค่า หรือ ตั้งค่าแบบอักษรหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

คืนค่า หรือ ตั้งค่าความสูงของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดว่าหัวข้อย่อยสืบทอดความสูงจากส่วนแรกของย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

คืนค่า หรือ ตั้งค่าความสูงของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดว่าหัวข้อย่อยสืบทอดความสูงจากส่วนแรกของย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

คืนค่ารูปแบบสีของหัวข้อย่อยของย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

คืนค่าภาพที่ใช้เป็นหัวข้อย่อยในย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [ISlidesPicture](../../com.aspose.slides/islidespicture).

**คืนค่า:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน short.

**คืนค่า:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

คืนค่า หรือ ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน short.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

คืนค่า หรือ ตั้งค่าสไตล์ของหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**คืนค่า:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

คืนค่า หรือ ตั้งค่าสไตล์ของหัวข้อย่อยแบบลำดับเลขที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

กำหนดว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool#True** หากหัวข้อย่อยมีสีของตนเองและ **NullableBool#False** หากหัวข้อย่อยสืบทอดสีจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

กำหนดว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool#True** หากหัวข้อย่อยมีสีของตนเองและ **NullableBool#False** หากหัวข้อย่อยสืบทอดสีจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

กำหนดว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool#True** หากหัวข้อย่อยมีแบบอักษรของตนเองและ **NullableBool#False** หากหัวข้อย่อยสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

กำหนดว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. **NullableBool#True** หากหัวข้อย่อยมีแบบอักษรของตนเองและ **NullableBool#False** หากหัวข้อย่อยสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

ตั้งค่าการยืดอิเล็กต์เริ่มต้นที่ไม่เป็นศูนย์สำหรับการเยื้องและ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้หัวข้อย่อย (เช่น PowerPoint ทำเมื่อเปิดใช้งานหัวข้อย่อย/การนับลำดับในย่อหน้า). หากปิดใช้หัวข้อย่อยก็จะรีเซ็ตการเยื้องและ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดใช้งานหัวข้อย่อย/การนับลำดับในย่อหน้า). การปรับเยื้องจะอ้างอิงตามบริบทของหัวข้อย่อยปัจจุบัน – IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การปรับเยื้องที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบหัวข้อย่อยที่มีผลพร้อมการสืบทอดที่ใช้.

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