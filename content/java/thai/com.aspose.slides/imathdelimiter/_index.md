---
title: IMathDelimiter
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุอ็อบเจ็กต์ตัวคั่นที่ประกอบด้วยอักขระเปิดและปิด เช่น วงเล็บ โค้ง วงเหลือก และเส้นตั้ง และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายในที่แยกด้วยอักขระที่ระบุ
type: docs
url: /th/com.aspose.slides/imathdelimiter/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

กำหนดอ็อบเจ็กต์ตัวคั่นที่ประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, โค้ง, วงเหลือก, และเส้นตั้ง) และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายใน แยกด้วยอักขระที่ระบุ ตัวอย่าง: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | หนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ที่แยกด้วยอักขระตัวคั่น |
| [getBeginningCharacter()](#getBeginningCharacter--) | อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | อักขระคั่นระหว่างระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจกต์ตัวคั่น |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | อักขระคั่นระหว่างระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจกต์ตัวคั่น |
| [getEndingCharacter()](#getEndingCharacter--) | อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่า true ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของตัวถูกสั่งการ |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่า true ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของตัวถูกสั่งการ |
| [getDelimiterShape()](#getDelimiterShape--) | ระบุรูปแบบของตัวคั่นในอ็อบเจกต์ตัวคั่น |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | ระบุรูปแบบของตัวคั่นในอ็อบเจกต์ตัวคั่น |
| [delimit(char separatorCharacter)](#delimit-char-) | แบ่งอาร์กิวเมนต์โดยใช้ตัวคั่นที่ระบุ |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract char getBeginningCharacter()
```

อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลือก, และโค้ง ค่าเริ่มต้น: '('.

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
public abstract void setBeginningCharacter(char value)
```

อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลือก, และโค้ง ค่าเริ่มต้น: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

อักขระคั่นระหว่างระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจกต์ตัวคั่น ค่าเริ่มต้น: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

อักขระคั่นระหว่างระบุอักขระที่แยกอาร์กิวเมนต์ในอ็อบเจกต์ตัวคั่น ค่าเริ่มต้น: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลือก, และโค้ง ค่าเริ่มต้น: ')'.

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
public abstract void setEndingCharacter(char value)
```

อักขระสิ้นสุดของตัวคั่นระบุอักขระสิ้นสุดหรืออักขระปิดของตัวคั่น ตัวคั่นคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่น วงเล็บ, วงเหลือก, และโค้ง ค่าเริ่มต้น: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่า true ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของตัวถูกสั่งการ ค่าเริ่มต้นคือ true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**คืนค่า:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่า true ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของตัวถูกสั่งการ ค่าเริ่มต้นคือ true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

ระบุรูปแบบของตัวคั่นในอ็อบเจกต์ตัวคั่น เมื่อเป็น MathDelimiterShape.Centered ตัวคั่นจะถูกจัดให้อยู่กึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปแบบของตัวคั่นจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**คืนค่า:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

ระบุรูปแบบของตัวคั่นในอ็อบเจกต์ตัวคั่น เมื่อเป็น MathDelimiterShape.Centered ตัวคั่นจะถูกจัดให้อยู่กึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปแบบของตัวคั่นจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

แบ่งอาร์กิวเมนต์โดยใช้ตัวคั่นที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| separatorCharacter | char | ตัวคั่น |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - อ็อบเจ็กต์นี้หลังจากนำตัวคั่นไปใช้