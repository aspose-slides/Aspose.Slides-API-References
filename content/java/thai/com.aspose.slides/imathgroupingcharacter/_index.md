---
title: IMathGroupingCharacter
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้ส่วนแสดงทั่วไปโดยปกติเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ
type: docs
url: /th/com.aspose.slides/imathgroupingcharacter/
---
**ส่วนติดต่อที่ทำงานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้ส่วนแสดงทั่วไป โดยมักใช้เพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนท์พื้นฐาน |
| [getCharacter()](#getCharacter--) | ค่าปริยายของอักขระการจัดกลุ่ม: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | ค่าปริยายของอักขระการจัดกลุ่ม: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [getVerticalJustification()](#getVerticalJustification--) | การจัดตำแหน่งแนวตั้งของอักขระการจัดกลุ่ม |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | การจัดตำแหน่งแนวตั้งของอักขระการจัดกลุ่ม |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนท์พื้นฐาน

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

ค่าปริยายของอักขระการจัดกลุ่ม: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // วงเล็บล่าง
> ```

**คืนค่า:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

ค่าปริยายของอักขระการจัดกลุ่ม: U+23DF (BOTTOM CURLY BRACKET)

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

**คืนค่า:**
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

การจัดตำแหน่งแนวตั้งของอักขระการจัดกลุ่ม ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระการจัดกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดตำแหน่งแนวตั้ง Top หมายความว่าด้านบนของอ็อบเจ็กต์ตกบนเส้นฐาน; เมื่อการจัดตำแหน่งแนวตั้งเป็น Bottom ด้านล่างของอ็อบเจ็กต์อยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**คืนค่า:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

การจัดตำแหน่งแนวตั้งของอักขระการจัดกลุ่ม ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระการจัดกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดตำแหน่งแนวตั้ง Top หมายความว่าด้านบนของอ็อบเจ็กต์ตกบนเส้นฐาน; เมื่อการจัดตำแหน่งแนวตั้งเป็น Bottom ด้านล่างของอ็อบเจ็กต์อยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

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