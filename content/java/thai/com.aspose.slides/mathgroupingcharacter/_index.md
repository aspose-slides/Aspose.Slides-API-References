---
title: MathGroupingCharacter
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุสัญลักษณ์การจัดกลุ่มที่อยู่เหนือหรือใต้การแสดงผลโดยปกติเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ
type: docs
url: /th/com.aspose.slides/mathgroupingcharacter/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ทำตามทั้งหมด:  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

ระบุสัญลักษณ์การจัดกลุ่มที่อยู่เหนือหรือใต้การแสดงผล โดยมักใช้เพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter ด้วยอักขระการจัดกลุ่มค่าดีฟอลต์ U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getCharacter()](#getCharacter--) | อักขระการจัดกลุ่ม ค่าดีฟอลต์: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | อักขระการจัดกลุ่ม ค่าดีฟอลต์: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | ตำแหน่งของอักขระการจัดกลุ่ม. |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของอักขระการจัดกลุ่ม. |
| [getVerticalJustification()](#getVerticalJustification--) | การจัดแนวแนวตั้งของอักขระกลุ่ม. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | การจัดแนวแนวตั้งของอักขระกลุ่ม. |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |

### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter ด้วยอักขระการจัดกลุ่มค่าดีฟอลต์ U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อีลีเมนต์ฐานที่บาร์ถูกนำไปใช้ |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อีลีเมนต์ฐานที่บาร์ถูกนำไปใช้ |
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

**ค่าที่คืนกลับ:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

อักขระการจัดกลุ่ม ค่าดีฟอลต์: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // วงเล็บล่าง
> ```

**ค่าที่คืนกลับ:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

อักขระการจัดกลุ่ม ค่าดีฟอลต์: U+23DF (BOTTOM CURLY BRACKET)

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

ตำแหน่งของอักขระการจัดกลุ่ม. ค่าเริ่มต้น: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**ค่าที่คืนกลับ:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

ตำแหน่งของอักขระการจัดกลุ่ม. ค่าเริ่มต้น: Bottom

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

การจัดแนวแนวตั้งของอักขระกลุ่ม. ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดแนวแนวตั้ง Top แสดงว่าบนของอ็อบเจ็กต์อยู่บนเส้นฐาน; เมื่อการจัดแนวแนวตั้งตั้งเป็น Bottom ส่วนล่างของอ็อบเจ็กต์จะอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**ค่าที่คืนกลับ:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

การจัดแนวแนวตั้งของอักขระกลุ่ม. ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์ การจัดแนวแนวตั้ง Top แสดงว่าบนของอ็อบเจ็กต์อยู่บนเส้นฐาน; เมื่อการจัดแนวแนวตั้งตั้งเป็น Bottom ส่วนล่างของอ็อบเจ็กต์จะอยู่บนเส้นฐาน ค่าเริ่มต้น: Bottom สำหรับ Position=Top และ Top สำหรับ Position=Bottom

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

รับองค์ประกอบลูก

**ค่าที่คืนกลับ:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่คืนกลับ:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps