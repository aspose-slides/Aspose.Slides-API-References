---
title: BulletFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคุณสมบัติการจัดรูปแบบบูลเล็ตของย่อหน้า.
type: docs
url: /th/com.aspose.slides/bulletformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)  
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

แสดงคุณสมบัติการจัดรูปแบบบูลเล็ตของย่อหน้า.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | ส่งคืนหรือกำหนดประเภทบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [setType(byte value)](#setType-byte-) | ส่งคืนหรือกำหนดประเภทบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [getChar()](#getChar--) | ส่งคืนหรือกำหนดอักขระบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [setChar(char value)](#setChar-char-) | ส่งคืนหรือกำหนดอักขระบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [getFont()](#getFont--) | ส่งคืนหรือกำหนดฟอนต์บูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | ส่งคืนหรือกำหนดฟอนต์บูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [getHeight()](#getHeight--) | ส่งคืนหรือกำหนดความสูงบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [setHeight(float value)](#setHeight-float-) | ส่งคืนหรือกำหนดความสูงบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [getColor()](#getColor--) | ส่งคืนรูปแบบสีของบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | ส่งคืนหรือกำหนดเลขแรกที่ใช้สำหรับกลุ่มบูลเล็ตลำดับที่ไม่มีการสืบทอด. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | ส่งคืนหรือกำหนดเลขแรกที่ใช้สำหรับกลุ่มบูลเล็ตลำดับที่ไม่มีการสืบทอด. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | ส่งคืนหรือกำหนดสไตล์ของบูลเล็ตลำดับที่ไม่มีการสืบทอด. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | ส่งคืนหรือกำหนดสไตล์ของบูลเล็ตลำดับที่ไม่มีการสืบทอด. |
| [isBulletHardColor()](#isBulletHardColor--) | กำหนดว่าบูลเล็ตมีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | กำหนดว่าบูลเล็ตมีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. |
| [isBulletHardFont()](#isBulletHardFont--) | กำหนดว่าบูลเล็ตมีฟอนต์ของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | กำหนดว่าบูลเล็ตมีฟอนต์ของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. |
| [getPicture()](#getPicture--) | ส่งคืนรูปภาพที่ใช้เป็นบูลเล็ตในย่อหน้าที่ไม่มีการสืบทอด. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | กำหนดการเลื่อนค่าไม่เป็นศูนย์เริ่มต้นสำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้บูลเล็ต (เช่น PowerPoint ทำเมื่อเปิดใช้งานบูลเล็ต/หมายเลขในย่อหน้า). |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบบูลเล็ตที่มีผลพร้อมการสืบทอดที่นำมาใช้. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

ส่งคืนหรือกำหนดประเภทบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**คืนค่า:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

ส่งคืนหรือกำหนดประเภทบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [BulletType](../../com.aspose.slides/bullettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

ส่งคืนหรือกำหนดอักขระบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  char .

**คืนค่า:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

ส่งคืนหรือกำหนดอักขระบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน  char .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

ส่งคืนหรือกำหนดฟอนต์บูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

ส่งคืนหรือกำหนดฟอนต์บูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

ส่งคืนหรือกำหนดความสูงบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดว่าบูลเล็ตสืบทอดความสูงจากส่วนแรกในย่อหน้า. อ่าน/เขียน  float .

**คืนค่า:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ส่งคืนหรือกำหนดความสูงบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. ค่า Float.NaN กำหนดว่าบูลเล็ตสืบทอดความสูงจากส่วนแรกในย่อหน้า. อ่าน/เขียน  float .

--------------------

ค่าความสูงที่เป็นลบหมายถึงความสูงเป็นจุด (points) และค่าบวกหมายถึงความสูงเป็นเปอร์เซ็นต์ของข้อความรอบข้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

ส่งคืนรูปแบบสีของบูลเล็ตของย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

ส่งคืนหรือกำหนดเลขแรกที่ใช้สำหรับกลุ่มบูลเล็ตลำดับที่ไม่มีการสืบทอด. อ่าน/เขียน  short .

**คืนค่า:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

ส่งคืนหรือกำหนดเลขแรกที่ใช้สำหรับกลุ่มบูลเล็ตลำดับที่ไม่มีการสืบทอด. อ่าน/เขียน  short .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

ส่งคืนหรือกำหนดสไตล์ของบูลเล็ตลำดับที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**คืนค่า:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

ส่งคืนหรือกำหนดสไตล์ของบูลเล็ตลำดับที่ไม่มีการสืบทอด. อ่าน/เขียน [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

กำหนดว่าบูลเล็ตมีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **NullableBool.True** หากบูลเล็ตมีสีของตัวเองและ **NullableBool.False** หากบูลเล็ตสืบทอดสีจากส่วนแรกในย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

กำหนดว่าบูลเล็ตมีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **NullableBool.True** หากบูลเล็ตมีสีของตัวเองและ **NullableBool.False** หากบูลเล็ตสืบทอดสีจากส่วนแรกในย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

กำหนดว่าบูลเล็ตมีฟอนต์ของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. ** NullableBool.True** หากบูลเล็ตมีฟอนต์ของตัวเองและ **NullableBool.False** หากบูลเล็ตสืบทอดฟอนต์จากส่วนแรกในย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

กำหนดว่าบูลเล็ตมีฟอนต์ของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **NullableBool.True** หากบูลเล็ตมีฟอนต์ของตัวเองและ **NullableBool.False** หากบูลเล็ตสืบทอดฟอนต์จากส่วนแรกในย่อหน้า. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

ส่งคืนรูปภาพที่ใช้เป็นบูลเล็ตในย่อหน้าที่ไม่มีการสืบทอด. อ่านอย่างเดียว [ISlidesPicture](../../com.aspose.slides/islidespicture).

**คืนค่า:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

กำหนดการเลื่อนค่าไม่เป็นศูนย์เริ่มต้นสำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้บูลเล็ต (เช่น PowerPoint ทำเมื่อเปิดใช้งานบูลเล็ต/หมายเลขในย่อหน้า). หากบูลเล็ตถูกปิด ระบบจะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่น PowerPoint ทำเมื่อปิดบูลเล็ต/หมายเลขในย่อหน้า). การเลื่อนค่า Indent ถูกนำมาใช้โดยอ้างอิงถึงบริบทบูลเล็ตปัจจุบัน – IBulletFormat.Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การเลื่อนค่าไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้าปัจจุบัน (ทำให้ค่าผลลัพธ์เป็นค่าท้องถิ่น).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบบูลเล็ตที่มีผลพร้อมการสืบทอดที่นำมาใช้.

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