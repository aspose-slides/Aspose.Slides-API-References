---
title: MathGroupingCharacter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้สมการโดยทั่วไปเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ
type: docs
url: /th/com.aspose.slides/mathgroupingcharacter/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือใต้สมการ โดยปกติใช้เพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter ด้วยอักขระการจัดกลุ่มค่าเริ่มต้น U+23DF (วงเล็บโค้งล่าง) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getCharacter()](#getCharacter--) | อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (วงเล็บโค้งล่าง) |
| [setCharacter(char value)](#setCharacter-char-) | อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (วงเล็บโค้งล่าง) |
| [getPosition()](#getPosition--) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของอักขระการจัดกลุ่ม |
| [getVerticalJustification()](#getVerticalJustification--) | การจัดแนวแนวตั้งของอักขระกลุ่ม |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | การจัดแนวแนวตั้งของอักขระกลุ่ม |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |

### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter ด้วยอักขระการจัดกลุ่มค่าเริ่มต้น U+23DF (วงเล็บโค้งล่าง)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่ใช้กับแถบ |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่ใช้กับแถบ |
| character | char | อักขระการจัดกลุ่ม |
| position | int | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | int | การจัดแนวแนวตั้งของอักขระกลุ่ม |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (วงเล็บโค้งล่าง)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // วงเล็บล่าง
> ```

**ค่าที่ส่งกลับ:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

อักขระการจัดกลุ่ม ค่าเริ่มต้น: U+23DF (วงเล็บโค้งล่าง)

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
public final int getPosition()
```

ตำแหน่งของอักขระการจัดกลุ่ม ค่าเริ่มต้น: ด้านล่าง

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**ค่าที่ส่งกลับ:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

ตำแหน่งของอักขระการจัดกลุ่ม ค่าเริ่มต้น: ด้านล่าง

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
public final int getVerticalJustification()
```

การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของวัตถุสัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ การจัดแนวแนวตั้งบน (Top) หมายถึงด้านบนของวัตถุอยู่บนเส้นฐาน; เมื่อกำหนดการจัดแนวแนวตั้งเป็นล่าง (Bottom) ด้านล่างของวัตถุจะอยู่บนเส้นฐาน ค่าเริ่มต้น: ล่างสำหรับ Position=บน, และบนสำหรับ Position=ล่าง

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**ค่าที่ส่งกลับ:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของวัตถุสัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือวัตถุ การจัดแนวแนวตั้งบน (Top) หมายถึงด้านบนของวัตถุอยู่บนเส้นฐาน; เมื่อกำหนดการจัดแนวแนวตั้งเป็นล่าง (Bottom) ด้านล่างของวัตถุจะอยู่บนเส้นฐาน ค่าเริ่มต้น: ล่างสำหรับ Position=บน, และบนสำหรับ Position=ล่าง

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงองค์ประกอบลูก

**ค่าที่ส่งกลับ:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่ส่งกลับ:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps