---
title: MathDelimiter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุอ็อบเจ็กต์ตัวคั่นซึ่งประกอบด้วยอักขระเปิดและปิด เช่น วงเล็บ ครอบ วงกลมเหลี่ยม และแถบแนวตั้ง และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายในซึ่งแยกด้วยอักขระที่ระบุ.
type: docs
url: /th/com.aspose.slides/mathdelimiter/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

ระบุอ็อบเจ็กต์ตัวคั่นซึ่งประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, ครอบ, วงกลมเหลี่ยม, และแถบแนวตั้ง) และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายใน, แยกด้วยอักขระที่ระบุ ตัวอย่าง: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | เริ่มต้น MathDelimiter ด้วยอีลเมนต์ที่ระบุเป็นอีลเมนต์ฐานเดียว |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | หนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ที่แยกด้วยอักขระตัวคั่น |
| [getBeginningCharacter()](#getBeginningCharacter--) | อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | อักขระคั่นของตัวคั่นระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวคั่น |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | อักขระคั่นของตัวคั่นระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวคั่น |
| [getEndingCharacter()](#getEndingCharacter--) | อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นจริง ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นจริง ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ |
| [getDelimiterShape()](#getDelimiterShape--) | ระบุรูปร่างของตัวคั่นในอ็อบเจ็กต์ตัวคั่น |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | ระบุรูปร่างของตัวคั่นในอ็อบเจ็กต์ตัวคั่น |
| [delimit(char separatorCharacter)](#delimit-char-) | แยกอาร์กิวเมนต์โดยใช้ตัวคั่นที่ระบุ |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | ใส่อีลเมนต์คณิตศาสตร์ในอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ |
| [getChildren()](#getChildren--) | รับอิลเมนต์ลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

เริ่มต้น MathDelimiter ด้วยอีลเมนต์ที่ระบุเป็นอีลเมนต์ฐานเดียว

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อีลเมนต์ฐานที่ตัวคั่นถูกนำไปใช้ สามารถเป็นค่า null |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

หนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ที่แยกด้วยอักขระตัวคั่น

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**คืนค่า:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระห่อหุ้มเช่นวงเล็บ, วงกลมเหลี่ยม, และครอบ ค่าเริ่มต้น: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**คืนค่า:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระห่อหุ้มเช่นวงเล็บ, วงกลมเหลี่ยม, และครอบ ค่าเริ่มต้น: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

อักขระคั่นของตัวคั่นระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวคั่น ค่าเริ่มต้น: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**คืนค่า:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

อักขระคั่นของตัวคั่นระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวคั่น ค่าเริ่มต้น: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระห่อหุ้มเช่นวงเล็บ, วงกลมเหลี่ยม, และครอบ ค่าเริ่มต้น: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**คืนค่า:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระห่อหุ้มเช่นวงเล็บ, วงกลมเหลี่ยม, และครอบ ค่าเริ่มต้น: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นจริง ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ ค่าเริ่มต้นคือ true

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**คืนค่า:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นจริง ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ ค่าเริ่มต้นคือ true

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

ระบุรูปร่างของตัวคั่นในอ็อบเจ็กต์ตัวคั่น เมื่อเป็น MathDelimiterShape.Centered ตัวคั่นจะอยู่ศูนย์กลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปร่างของมันจะถูกปรับเพื่อให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**คืนค่า:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

ระบุรูปร่างของตัวคั่นในอ็อบเจ็กต์ตัวคั่น เมื่อเป็น MathDelimiterShape.Centered ตัวคั่นจะอยู่ศูนย์กลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปร่างของมันจะถูกปรับเพื่อให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

แยกอาร์กิวเมนต์โดยใช้ตัวคั่นที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char | อักขระตัวคั่น |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - วัตถุนี้หลังจากใช้ตัวคั่น

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

ใส่อีลเมนต์คณิตศาสตร์ในอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | อักขระเริ่มต้น (โดยทั่วไปคือวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (โดยทั่วไปคือวงเล็บขวา) |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - หาก beginningCharacter และ endingCharacter เป็น null จะมีการกำหนดค่าให้กับคุณสมบัติเพียงเท่านั้นและจะไม่สร้างอ็อบเจ็กต์ใหม่ (คืนค่าอินสแตนซ์นี้) มิฉะนั้น จะคืนค่าอีลเมนต์คณิตศาสตร์ใหม่ประเภท Delimiter ซึ่งรวมอักขระที่ระบุเป็นกรอบและอินสแตนซ์ของ [MathDelimiter](../../com.aspose.slides/mathdelimiter) นี้อยู่ภายในกรอบ

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับอิลเมนต์ลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps