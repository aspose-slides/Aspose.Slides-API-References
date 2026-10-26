---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /th/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการฟอร์แมตของย่อหน้าโดยมีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IParagraphFormat](../../com.aspose.slides/iparagraphformat) เพื่อส่งคืนค่าการฟอร์แมตที่มีประสิทธิภาพโดยใช้การสืบทอด

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | ส่งคืนรูปแบบหัวข้อจุดของย่อหน้า |
| [getDepth()](#getDepth--) | ส่งคืนระดับความลึกของย่อหน้า |
| [getAlignment()](#getAlignment--) | ส่งคืนการจัดตำแหน่งข้อความในย่อหน้า |
| [getSpaceWithin()](#getSpaceWithin--) | ส่งคืนปริมาณพื้นที่ระหว่างบรรทัดฐานในย่อหน้า |
| [getSpaceBefore()](#getSpaceBefore--) | ส่งคืนปริมาณพื้นที่ก่อนบรรทัดแรกในย่อหน้า |
| [getSpaceAfter()](#getSpaceAfter--) | ส่งคืนปริมาณพื้นที่หลังบรรทัดสุดท้ายในย่อหน้า |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่ |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ |
| [getLatinLineBreak()](#getLatinLineBreak--) | กำหนดว่ามีการใช้การตัดบรรทัดแบบละตินในย่อหน้าหรือไม่ |
| [getHangingPunctuation()](#getHangingPunctuation--) | กำหนดว่ามีการใช้เครื่องหมายวรรคตอนแบบ hanging ในย่อหน้าหรือไม่ |
| [getMarginLeft()](#getMarginLeft--) | ส่งคืนขอบซ้ายในย่อหน้า |
| [getMarginRight()](#getMarginRight--) | ส่งคืนขอบขวาในย่อหน้า |
| [getIndent()](#getIndent--) | ส่งคืนการเยื้องบรรทัดแรก/การเยื้องแบบ hanging ของย่อหน้า |
| [getDefaultTabSize()](#getDefaultTabSize--) | ส่งคืนขนาดแท็บพื้นฐาน |
| [getTabs()](#getTabs--) | ส่งคืนแท็บของย่อหน้า |
| [getFontAlignment()](#getFontAlignment--) | ส่งคืนการจัดตำแหน่งฟอนต์ในย่อหน้า |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | ส่งคืนรูปแบบส่วนประกอบพื้นฐานของย่อหน้า |

### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

ส่งคืนรูปแบบหัวข้อจุดของย่อหน้า อ่านอย่างเดียว [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**คืนค่า:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

ส่งคืนระดับความลึกของย่อหน้า อ่านอย่างเดียว short.

**คืนค่า:**
short

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

ส่งคืนการจัดตำแหน่งข้อความในย่อหน้า อ่านอย่างเดียว [TextAlignment](../../com.aspose.slides/textalignment).

**คืนค่า:**
int

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

ส่งคืนปริมาณพื้นที่ระหว่างบรรทัดฐานในย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

ส่งคืนปริมาณพื้นที่ก่อนบรรทัดแรกในย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

ส่งคืนปริมาณพื้นที่หลังบรรทัดสุดท้ายในย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

กำหนดว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

กำหนดว่ามีการใช้การตัดบรรทัดแบบละตินในย่อหน้าหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

กำหนดว่ามีการใช้เครื่องหมายวรรคตอนแบบ hanging ในย่อหน้าหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

ส่งคืนขอบซ้ายในย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

ส่งคืนขอบขวาในย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

ส่งคืนการเยื้องบรรทัดแรก/การเยื้องแบบ hanging ของย่อหน้า การเยื้องแบบ hanging สามารถกำหนดด้วยค่าติดลบได้ อ่านอย่างเดียว float.

**คืนค่า:**
float

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

ส่งคืนขนาดแท็บพื้นฐาน อ่านอย่างเดียว float.

**คืนค่า:**
float

### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

ส่งคืนแท็บของย่อหน้า อ่านอย่างเดียว ITabEffectiveData[].

**คืนค่า:**
com.aspose.slides.ITabEffectiveData[]

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

ส่งคืนการจัดตำแหน่งฟอนต์ในย่อหน้า อ่านอย่างเดียว [FontAlignment](../../com.aspose.slides/fontalignment).

**คืนค่า:**
int

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

ส่งคืนรูปแบบส่วนประกอบพื้นฐานของย่อหน้า อ่านอย่างเดียว [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**คืนค่า:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)