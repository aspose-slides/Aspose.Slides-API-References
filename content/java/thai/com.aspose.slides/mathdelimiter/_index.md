---
title: MathDelimiter
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุอ็อบเจ็กต์ตัวแบ่งซึ่งประกอบด้วยอักขระเปิดและปิด เช่น วงเล็บ, ปีกกา, วงกรอบ และแถบแนวตั้ง รวมทั้งหนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ภายในที่แยกด้วยอักขระที่ระบุ
type: docs
url: /th/com.aspose.slides/mathdelimiter/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำงานทั้งหมด:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

ระบุอ็อบเจ็กต์ตัวแบ่งซึ่งประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, เครื่องหมายปีกกา, วงกรอบ, และเส้นตั้ง) และหนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ภายใน ซึ่งแยกโดยอักขระที่ระบุ ตัวอย่าง: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | เริ่มต้น MathDelimiter ด้วยอีลเมนต์ที่ระบุเป็นอาร์กิวเมนต์ฐานเดียว |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่แยกด้วยอักขระตัวแบ่ง |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character ระบุอักขระตัวแบ่งที่เป็นจุดเริ่มต้นหรือเปิด |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character ระบุอักขระตัวแบ่งที่เป็นจุดเริ่มต้นหรือเปิด |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character ระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวแบ่ง |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character ระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวแบ่ง |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character ระบุอักขระตัวแบ่งที่เป็นจุดสิ้นสุดหรือปิด |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character ระบุอักขระตัวแบ่งที่เป็นจุดสิ้นสุดหรือปิด |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true ตัวแบ่งจะขยายแนวตั้งเพื่อให้ตรงกับความสูงของออแพอแรนด์ |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true ตัวแบ่งจะขยายแนวตั้งเพื่อให้ตรงกับความสูงของออแพอแรนด์ |
| [getDelimiterShape()](#getDelimiterShape--) | ระบุรูปร่างของตัวแบ่งในอ็อบเจ็กต์ตัวแบ่ง |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | ระบุรูปร่างของตัวแบ่งในอ็อบเจ็กต์ตัวแบ่ง |
| [delimit(char separatorCharacter)](#delimit-char-) | กำหนดขอบเขตอาร์กิวเมนต์โดยใช้ตัวอักษรตัวแบ่งที่ระบุ |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | ห่อหุ้มอีลเมนต์คณิตศาสตร์ด้วยอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ |
| [getChildren()](#getChildren--) | รับอีลเมนต์ลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติวิเศษของอักขระควบคุม |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


เริ่มต้น MathDelimiter ด้วยอีลเมนต์ที่ระบุเป็นอาร์กิวเมนต์ฐานเดียว

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อีลเมนต์ฐานที่ตัวแบ่งถูกนำไปใช้ สามารถเป็น null ได้ |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่แยกด้วยอักขระตัวแบ่ง

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**ค่าที่ส่งคืน:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```


Delimiter Beginning Character ระบุอักขระตัวแบ่งที่เป็นจุดเริ่มต้นหรือเปิด ตัวแบ่งทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงกรอบ, และปีกกา ค่าเริ่มต้น: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**ค่าที่ส่งคืน:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```


Delimiter Beginning Character ระบุอักขระตัวแบ่งที่เป็นจุดเริ่มต้นหรือเปิด ตัวแบ่งทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงกรอบ, และปีกกา ค่าเริ่มต้น: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```


Delimiter Separator Character ระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวแบ่ง ค่าเริ่มต้น: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**ค่าที่ส่งคืน:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```


Delimiter Separator Character ระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ตัวแบ่ง ค่าเริ่มต้น: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```


Delimiter Ending Character ระบุอักขระตัวแบ่งที่เป็นจุดสิ้นสุดหรือปิด ตัวแบ่งทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงกรอบ, และปีกกา ค่าเริ่มต้น: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**ค่าที่ส่งคืน:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```


Delimiter Ending Character ระบุอักขระตัวแบ่งที่เป็นจุดสิ้นสุดหรือปิด ตัวแบ่งทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงกรอบ, และปีกกา ค่าเริ่มต้น: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true ตัวแบ่งจะขยายแนวตั้งเพื่อให้ตรงกับความสูงของออแพอแรนด์ ค่าเริ่มต้นคือ true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**ค่าที่ส่งคืน:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true ตัวแบ่งจะขยายแนวตั้งเพื่อให้ตรงกับความสูงของออแพอแรนด์ ค่าเริ่มต้นคือ true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```


ระบุรูปร่างของตัวแบ่งในอ็อบเจ็กต์ตัวแบ่ง เมื่อเป็น MathDelimiterShape.Centered ตัวแบ่งจะถูกจัดกึ่งกลางตามแกนคณิตศาสตร์ของข้อความและยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**ค่าที่ส่งคืน:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```


ระบุรูปร่างของตัวแบ่งในอ็อบเจ็กต์ตัวแบ่ง เมื่อเป็น MathDelimiterShape.Centered ตัวแบ่งจะถูกจัดกึ่งกลางตามแกนคณิตศาสตร์ของข้อความและยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


กำหนดขอบเขตอาร์กิวเมนต์โดยใช้ตัวอักษรตัวแบ่งที่ระบุ

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char | อักขระตัวแบ่ง |

**ค่าที่ส่งคืน:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - อ็อบเจ็กต์นี้หลังจากนำอักขระตัวแบ่งไปใช้
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


ห่อหุ้มอีลเมนต์คณิตศาสตร์ด้วยอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**พารามิเตอร์:**
| Parameter | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | ตัวอักขระเริ่มต้น (โดยทั่วไปคือวงเล็บซ้าย) |
| endingCharacter | char | ตัวอักขระสิ้นสุด (โดยทั่วไปคือวงเล็บขวา) |

**ค่าที่ส่งคืน:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - หาก beginningCharacter และ endingCharacter เป็น null จะมีการกำหนดค่าให้กับคุณสมบัติเจ้าพร้อมกันเท่านั้นและไม่มีการสร้างอ็อบเจ็กต์ใหม่ (ส่งคืนอินสแตนซ์นี้) มิฉะนั้น จะส่งคืนอีลเมนต์คณิตศาสตร์ใหม่ชนิด Delimiter ซึ่งรวมอักขระที่ระบุเป็นกรอบและอินสแตนซ์ของ [MathDelimiter](../../com.aspose.slides/mathdelimiter) นี้อยู่ภายใน
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


รับอีลเมนต์ลูก

**ค่าที่ส่งคืน:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


คุณสมบัติวิเศษของอักขระควบคุม

**ค่าที่ส่งคืน:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps