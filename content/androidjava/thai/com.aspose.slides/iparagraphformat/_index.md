---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /th/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า ในทางตรงกันข้ามกับ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้

--------------------

คลาสนี้ใช้เพื่อรับและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าที่ระบุ หมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “ไม่กำหนด”

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้วิธี [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) ซึ่งจะคืนค่าอินสแตนซ์ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | ส่งคืนรูปแบบหัวข้อของย่อหน้า |
| [getDepth()](#getDepth--) | ส่งคืนหรือกำหนดความลึกของย่อหน้า |
| [setDepth(short value)](#setDepth-short-) | ส่งคืนหรือกำหนดความลึกของย่อหน้า |
| [getAlignment()](#getAlignment--) | ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด |
| [setAlignment(int value)](#setAlignment-int-) | ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด |
| [getSpaceWithin()](#getSpaceWithin--) | ส่งคืนหรือกำหนดปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | ส่งคืนหรือกำหนดปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า |
| [getSpaceBefore()](#getSpaceBefore--) | ส่งคืนหรือกำหนดปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | ส่งคืนหรือกำหนดปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด |
| [getSpaceAfter()](#getSpaceAfter--) | ส่งคืนหรือกำหนดปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | ส่งคืนหรือกำหนดปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ |
| [getRightToLeft()](#getRightToLeft--) | ตรวจสอบว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่ |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | ตรวจสอบว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่ |
| [getLatinLineBreak()](#getLatinLineBreak--) | ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ |
| [getHangingPunctuation()](#getHangingPunctuation--) | ตรวจสอบว่าการใช้เครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | ตรวจสอบว่าการใช้เครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ |
| [getMarginLeft()](#getMarginLeft--) | ส่งคืนหรือกำหนดระยะขอบด้านซ้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [setMarginLeft(float value)](#setMarginLeft-float-) | ส่งคืนหรือกำหนดระยะขอบด้านซ้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [getMarginRight()](#getMarginRight--) | ส่งคืนหรือกำหนดระยะขอบด้านขวาในย่อหน้าโดยไม่มีการสืบทอด |
| [setMarginRight(float value)](#setMarginRight-float-) | ส่งคืนหรือกำหนดระยะขอบด้านขวาในย่อหน้าโดยไม่มีการสืบทอด |
| [getIndent()](#getIndent--) | ส่งคืนหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด |
| [setIndent(float value)](#setIndent-float-) | ส่งคืนหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด |
| [getDefaultTabSize()](#getDefaultTabSize--) | ส่งคืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | ส่งคืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด |
| [getTabs()](#getTabs--) | ส่งคืนแท็บของย่อหน้า |
| [getFontAlignment()](#getFontAlignment--) | ส่งคืนหรือกำหนดการจัดแนวแบบอักษรในย่อหน้าโดยไม่มีการสืบทอด |
| [setFontAlignment(int value)](#setFontAlignment-int-) | ส่งคืนหรือกำหนดการจัดแนวแบบอักษรในย่อหน้าโดยไม่มีการสืบทอด |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | ส่งคืนรูปแบบส่วนย่อยปริยายของย่อหน้า |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยมีการสืบทอด |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

ส่งคืนรูปแบบหัวข้อของย่อหน้า อ่านอย่างเดียว [IBulletFormat](../../com.aspose.slides/ibulletformat).

**ค่าที่ส่งคืน:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

ส่งคืนหรือกำหนดความลึกของย่อหน้า ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด อ่าน/เขียน short.

**ค่าที่ส่งคืน:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

ส่งคืนหรือกำหนดความลึกของย่อหน้า ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด อ่าน/เขียน short.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**ค่าที่ส่งคืน:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

ส่งคืนหรือกำหนดปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ ค่าเป็นลบหมายถึงขนาดในหน่วยจุด ไม่มีการสืบทอด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

ส่งคืนหรือกำหนดปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ ค่าเป็นลบหมายถึงขนาดในหน่วยจุด ไม่มีการสืบทอด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

ส่งคืนหรือกำหนดปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด ค่าบวกระบุเป็นเปอร์เซ็นต์ของขนาดฟอนต์ ค่าลบระบุเป็นขนาดจุด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

ส่งคืนหรือกำหนดปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด ค่าบวกระบุเป็นเปอร์เซ็นต์ของขนาดฟอนต์ ค่าลบระบุเป็นขนาดจุด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

ส่งคืนหรือกำหนดปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด ค่าบวกระบุเป็นเปอร์เซ็นต์ของขนาดฟอนต์ ค่าลบระบุเป็นขนาดจุด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

ส่งคืนหรือกำหนดปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด ค่าบวกระบุเป็นเปอร์เซ็นต์ของขนาดฟอนต์ ค่าลบระบุเป็นขนาดจุด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ค่าที่ส่งคืน:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

ตรวจสอบว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ค่าที่ส่งคืน:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

ตรวจสอบว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ค่าที่ส่งคืน:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

ตรวจสอบว่าการใช้เครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**ค่าที่ส่งคืน:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

ตรวจสอบว่าการใช้เครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ ไม่มีการสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

ส่งคืนหรือกำหนดระยะขอบด้านซ้ายในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

ส่งคืนหรือกำหนดระยะขอบด้านซ้ายในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

ส่งคืนหรือกำหนดระยะขอบด้านขวาในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

ส่งคืนหรือกำหนดระยะขอบด้านขวาในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

ส่งคืนหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด การเยื้องแบบห้อยสามารถกำหนดด้วยค่าเป็นลบ อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

ส่งคืนหรือกำหนดการเยื้อนบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด การเยื้องแบบห้อยสามารถกำหนดด้วยค่าเป็นลบ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

ส่งคืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด อ่าน/เขียน float.

**ค่าที่ส่งคืน:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

ส่งคืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

ส่งคืนแท็บของย่อหน้า ไม่มีการสืบทอด อ่านอย่างเดียว [ITabCollection](../../com.aspose.slides/itabcollection).

**ค่าที่ส่งคืน:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

ส่งคืนหรือกำหนดการจัดแนวแบบอักษรในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**ค่าที่ส่งคืน:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

ส่งคืนหรือกำหนดการจัดแนวแบบอักษรในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

ส่งคืนรูปแบบส่วนย่อยปริยายของย่อหน้า ไม่มีการสืบทอด อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

**ค่าที่ส่งคืน:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยมีการสืบทอด

**ค่าที่ส่งคืน:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).