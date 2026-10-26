---
title: IChartParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคุณสมบัติการจัดรูปแบบย่อหน้าของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartparagraphformat/
---```
public interface IChartParagraphFormat
```

แสดงคุณสมบัติการจัดรูปแบบย่อหน้าของแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAlignment()](#getAlignment--) | คืนค่า หรือ ตั้งค่าการจัดแนวข้อความในย่อหน้า. |
| [setAlignment(int value)](#setAlignment-int-) | คืนค่า หรือ ตั้งค่าการจัดแนวข้อความในย่อหน้า. |
| [getSpaceWithin()](#getSpaceWithin--) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า. |
| [getSpaceBefore()](#getSpaceBefore--) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. |
| [getSpaceAfter()](#getSpaceAfter--) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | คืนค่า หรือ ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | กำหนดว่าการแบ่งบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | กำหนดว่าการแบ่งบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. |
| [getLatinLineBreak()](#getLatinLineBreak--) | กำหนดว่าการแบ่งบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | กำหนดว่าการแบ่งบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่. |
| [getHangingPunctuation()](#getHangingPunctuation--) | กำหนดว่าการวางเครื่องหมายวรรคตอนแขวนถูกใช้ในย่อหน้าหรือไม่. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | กำหนดว่าการวางเครื่องหมายวรรคตอนแขวนถูกใช้ในย่อหน้าหรือไม่. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่า หรือ ตั้งค่าขอบซ้ายในย่อหน้า. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | คืนค่า หรือ ตั้งค่าขอบซ้ายในย่อหน้า. |
| [getMarginRight()](#getMarginRight--) | คืนค่า หรือ ตั้งค่าขอบขวาในย่อหน้า. |
| [setMarginRight(float value)](#setMarginRight-float-) | คืนค่า หรือ ตั้งค่าขอบขวาในย่อหน้า. |
| [getIndent()](#getIndent--) | คืนค่า หรือ ตั้งค่าการเยื้องบรรทัดแรก/เยื้องแขวนของย่อหน้า. |
| [setIndent(float value)](#setIndent-float-) | คืนค่า หรือ ตั้งค่าการเยื้องบรรทัดแรก/เยื้องแขวนของย่อหน้า. |
| [getDefaultTabSize()](#getDefaultTabSize--) | คืนค่า หรือ ตั้งค่าขนาดการแท็บเริ่มต้น. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | คืนค่า หรือ ตั้งค่าขนาดการแท็บเริ่มต้น. |
| [getTabs()](#getTabs--) | คืนค่าการแท็บของย่อหน้า. |
| [getFontAlignment()](#getFontAlignment--) | คืนค่า หรือ ตั้งค่าการจัดแนวฟอนต์ในย่อหน้า. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | คืนค่า หรือ ตั้งค่าการจัดแนวฟอนต์ในย่อหน้า. |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

คืนค่า หรือ ตั้งค่าการจัดแนวข้อความในย่อหน้า. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**คืนค่า:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

คืนค่า หรือ ตั้งค่าการจัดแนวข้อความในย่อหน้า. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างระหว่างเส้นฐานในย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

คืนค่า หรือ ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

กำหนดว่าการแบ่งบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

กำหนดว่าการแบ่งบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

กำหนดว่าการแบ่งบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

กำหนดว่าการแบ่งบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

กำหนดว่าการวางเครื่องหมายวรรคตอนแขวนถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

กำหนดว่าการวางเครื่องหมายวรรคตอนแขวนถูกใช้ในย่อหน้าหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

คืนค่า หรือ ตั้งค่าขอบซ้ายในย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

คืนค่า หรือ ตั้งค่าขอบซ้ายในย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

คืนค่า หรือ ตั้งค่าขอบขวาในย่อหน้า. อ่าน/เขียน float.

**คืนค่า:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

คืนค่า หรือ ตั้งค่าขอบขวาในย่อหน้า. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

คืนค่า หรือ ตั้งค่าการเยื้องบรรทัดแรก/เยื้องแขวนของย่อหน้า. การเยื้องแขวนสามารถกำหนดด้วยค่าติดลบได้. อ่าน/เขียน float.

**คืนค่า:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

คืนค่า หรือ ตั้งค่าการเยื้องบรรทัดแรก/เยื้องแขวนของย่อหน้า. การเยื้องแขวนสามารถกำหนดด้วยค่าติดลบได้. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

คืนค่า หรือ ตั้งค่าขนาดการแท็บเริ่มต้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

คืนค่า หรือ ตั้งค่าขนาดการแท็บเริ่มต้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

คืนค่าการแท็บของย่อหน้า. อ่านอย่างเดียว [ITabCollection](../../com.aspose.slides/itabcollection).

**คืนค่า:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

คืนค่า หรือ ตั้งค่าการจัดแนวฟอนต์ในย่อหน้า. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**คืนค่า:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

คืนค่า หรือ ตั้งค่าการจัดแนวฟอนต์ในย่อหน้า. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |