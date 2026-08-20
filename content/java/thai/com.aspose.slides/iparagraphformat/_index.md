---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า.
type: docs
url: /th/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า. แตกต่างจาก [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

คลาสนี้ใช้เพื่อดึงคืนและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดใช้เมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้ค่าที่หมายถึง “undefined”.

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงค่าที่สืบทอด คุณต้องใช้เมธอด [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) ซึ่งจะคืนค่าตัวอย่าง [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | คืนค่ารูปแบบหัวข้อของย่อหน้า. |
| [getDepth()](#getDepth--) | คืนค่าหรือกำหนดความลึกของย่อหน้า. |
| [setDepth(short value)](#setDepth-short-) | คืนค่าหรือกำหนดความลึกของย่อหน้า. |
| [getAlignment()](#getAlignment--) | คืนค่าหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. |
| [setAlignment(int value)](#setAlignment-int-) | คืนค่าหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. |
| [getSpaceWithin()](#getSpaceWithin--) | คืนค่าหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | คืนค่าหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า. |
| [getSpaceBefore()](#getSpaceBefore--) | คืนค่าหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | คืนค่าหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. |
| [getSpaceAfter()](#getSpaceAfter--) | คืนค่าหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | คืนค่าหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดเอเชียตะวันออกในย่อหน้าหรือไม่. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | กำหนดว่ามีการใช้การตัดบรรทัดเอเชียตะวันออกในย่อหน้าหรือไม่. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. |
| [getLatinLineBreak()](#getLatinLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | กำหนดว่ามีการใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. |
| [getHangingPunctuation()](#getHangingPunctuation--) | กำหนดว่ามีการใช้เครื่องหมายวรรคตอนห้อยในย่อหน้าหรือไม่. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | กำหนดว่ามีการใช้เครื่องหมายวรรคตอนห้อยในย่อหน้าหรือไม่. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | คืนค่าหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. |
| [setMarginRight(float value)](#setMarginRight-float-) | คืนค่าหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. |
| [getIndent()](#getIndent--) | คืนค่าหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. |
| [setIndent(float value)](#setIndent-float-) | คืนค่าหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. |
| [getDefaultTabSize()](#getDefaultTabSize--) | คืนค่าหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | คืนค่าหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด. |
| [getTabs()](#getTabs--) | คืนค่าแท็บของย่อหน้า. |
| [getFontAlignment()](#getFontAlignment--) | คืนค่าหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | คืนค่าหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | คืนค่ารูปแบบส่วนเริ่มต้นของย่อหน้า. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยมีการสืบทอด. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

คืนค่ารูปแบบหัวข้อของย่อหน้า. อ่านอย่างเดียว [IBulletFormat](../../com.aspose.slides/ibulletformat).

**คืนค่า:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

คืนค่าหรือกำหนดความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน short.

**คืนค่า:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

คืนค่าหรือกำหนดความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน short.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

คืนค่าหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**คืนค่า:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

คืนค่าหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

คืนค่าหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า. ค่าบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดในจุด. ไม่ใช้การสืบทอด. อ่าน/เขียน float.

**คืนค่า:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

คืนค่าหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า. ค่าบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดในจุด. ไม่ใช้การสืบทอด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

คืนค่าหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ของขนาดฟอนต์, ค่าเป็นลบหมายถึงขนาดช่องว่างเป็นจุด. อ่าน/เขียน float.

**คืนค่า:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

คืนค่าหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ของขนาดฟอนต์, ค่าเป็นลบหมายถึงขนาดช่องว่างเป็นจุด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

คืนค่าหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ของขนาดฟอนต์, ค่าเป็นลบหมายถึงขนาดช่องว่างเป็นจุด. อ่าน/เขียน float.

**คืนค่า:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

คืนค่าหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ของขนาดฟอนต์, ค่าเป็นลบหมายถึงขนาดช่องว่างเป็นจุด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

กำหนดว่ามีการใช้การตัดบรรทัดเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

กำหนดว่ามีการใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

กำหนดว่ามีการใช้เครื่องหมายวรรคตอนห้อยในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

กำหนดว่ามีการใช้เครื่องหมายวรรคตอนห้อยในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

คืนค่าหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**คืนค่า:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

คืนค่าหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

คืนค่าหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**คืนค่า:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

คืนค่าหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

คืนค่าหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องห้อยสามารถกำหนดด้วยค่าติดลบ. อ่าน/เขียน float.

**คืนค่า:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

คืนค่าหรือกำหนดการเยื้องบรรทัดแรก/การเยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องห้อยสามารถกำหนดด้วยค่าติดลบ. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

คืนค่าหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**คืนค่า:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

คืนค่าหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

คืนค่าแท็บของย่อหน้า. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [ITabCollection](../../com.aspose.slides/itabcollection).

**คืนค่า:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

คืนค่าหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**คืนค่า:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

คืนค่าหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

คืนค่ารูปแบบส่วนเริ่มต้นของย่อหน้า. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยมีการสืบทอด.

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).