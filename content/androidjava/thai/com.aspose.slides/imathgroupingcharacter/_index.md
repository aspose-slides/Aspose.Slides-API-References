---
title: IMathGroupingCharacter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้การแสดงผลโดยทั่วไปเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ
type: docs
url: /th/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้การแสดงผล ปกติเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
>  ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getCharacter()](#getCharacter--) | อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [getVerticalJustification()](#getVerticalJustification--) | การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**ค่าที่คืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // วงเล็บล่าง
> ```

**ค่าที่คืน:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // วงเล็บล่าง
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

ตำแหน่งของอักขระการจัดกลุ่ม ค่าเริ่มต้น: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**ค่าที่คืน:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

ตำแหน่งของอักขระการจัดกลุ่ม ค่าเริ่มต้น: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม ระบุการจัดแนวของอ็อบเจ็กต์ตามเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดตำแหน่งแนวตั้ง Top หมายถึงส่วนบนของอ็อบเจ็กต์อยู่บนเส้นฐาน; เมื่อกำหนดเป็น Bottom ส่วนล่างของอ็อบเจ็กต์จะอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom เมื่อ Position=Top และ Top เมื่อ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**ค่าที่คืน:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม ระบุการจัดแนวของอ็อบเจ็กต์ตามเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดตำแหน่งแนวตั้ง Top หมายถึงส่วนบนของอ็อบเจ็กต์อยู่บนเส้นฐาน; เมื่อกำหนดเป็น Bottom ส่วนล่างของอ็อบเจ็กต์จะอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom เมื่อ Position=Top และ Top เมื่อ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |