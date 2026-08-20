---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: อ็อบเจกต์ไม่เปลี่ยนแปลงที่มีคุณสมบัติการจัดรูปแบบย่อหน้าที่มีผลบังคับใช้.
type: docs
url: /th/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

อ็อบเจกต์ไม่เปลี่ยนแปลงที่มีคุณสมบัติการจัดรูปแบบย่อหน้าที่มีผลบังคับใช้.

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IParagraphFormat](../../com.aspose.slides/iparagraphformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยนำการสืบทอดมาประยุกต์ใช้.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | คืนรูปแบบหัวข้อย่อยของย่อหน้า. |
| [getDepth()](#getDepth--) | คืนค่าความลึกของย่อหน้า. |
| [getAlignment()](#getAlignment--) | คืนการจัดตำแหน่งข้อความในย่อหน้า. |
| [getSpaceWithin()](#getSpaceWithin--) | คืนค่าปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. |
| [getSpaceBefore()](#getSpaceBefore--) | คืนค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. |
| [getSpaceAfter()](#getSpaceAfter--) | คืนค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดสำหรับเอเชียตะวันออกในย่อหน้าหรือไม่. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. |
| [getLatinLineBreak()](#getLatinLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดสำหรับลาตินในย่อหน้าหรือไม่. |
| [getHangingPunctuation()](#getHangingPunctuation--) | กำหนดว่ามีการใช้เครื่องหมายวรรคตอนลอยในย่อหน้าหรือไม่. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าขอบซ้ายในย่อหน้า. |
| [getMarginRight()](#getMarginRight--) | คืนค่าขอบขวาในย่อหน้า. |
| [getIndent()](#getIndent--) | คืนค่าการเยื้องบรรทัดแรก/การเยื้องลอยของย่อหน้า. |
| [getDefaultTabSize()](#getDefaultTabSize--) | คืนขนาดแท็บเริ่มต้น. |
| [getTabs()](#getTabs--) | คืนการแท็บของย่อหน้า. |
| [getFontAlignment()](#getFontAlignment--) | คืนการจัดแนวฟอนต์ในย่อหน้า. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | คืนรูปแบบส่วนเริ่มต้นของย่อหน้า. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

คืนรูปแบบหัวข้อย่อยของย่อหน้า. อ่านอย่างเดียว [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**คืนค่า:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

คืนค่าความลึกของย่อหน้า. อ่านอย่างเดียว short.

**คืนค่า:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

คืนการจัดตำแหน่งข้อความในย่อหน้า. อ่านอย่างเดียว [TextAlignment](../../com.aspose.slides/textalignment).

**คืนค่า:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

คืนค่าปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

คืนค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

คืนค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดสำหรับเอเชียตะวันออกในย่อหน้าหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดสำหรับลาตินในย่อหน้าหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

กำหนดว่ามีการใช้เครื่องหมายวรรคตอนลอยในย่อหน้าหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

คืนค่าขอบซ้ายในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

คืนค่าขอบขวาในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

คืนค่าการเยื้องบรรทัดแรก/การเยื้องลอยของย่อหน้า. การเยื้องลอยสามารถกำหนดด้วยค่าเชิงลบได้. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

คืนขนาดแท็บเริ่มต้น. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

คืนการแท็บของย่อหน้า. อ่านอย่างเดียว ITabEffectiveData[].

**คืนค่า:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

คืนการจัดแนวฟอนต์ในย่อหน้า. อ่านอย่างเดียว [FontAlignment](../../com.aspose.slides/fontalignment).

**คืนค่า:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

คืนรูปแบบส่วนเริ่มต้นของย่อหน้า. อ่านอย่างเดียว [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**คืนค่า:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)