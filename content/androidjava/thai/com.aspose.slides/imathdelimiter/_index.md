---
title: IMathDelimiter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: ระบุวัตถุ delimiter ที่ประกอบด้วยอักขระเปิดและปิด เช่น วงเล็บ ปีกกา วงห่วง และแถบแนวตั้ง และหนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ภายในที่แยกด้วยอักขระที่กำหนด
type: docs
url: /th/com.aspose.slides/imathdelimiter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

ระบุวัตถุ delimiter ที่ประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ ปีกกา วงห่วง และแถบแนวตั้ง) และหนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ภายใน ซึ่งแยกด้วยอักขระที่กำหนด ตัวอย่าง: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่แยกด้วยอักขระ delimiter |
| [getBeginningCharacter()](#getBeginningCharacter--) | ตัวอักษรเริ่มต้นของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | ตัวอักษรเริ่มต้นของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | ตัวอักษรตัวคั่นของ Delimiter กำหนดอักขระที่แยกอาร์กิวเมนต์ในวัตถุ delimiter |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | ตัวอักษรตัวคั่นของ Delimiter กำหนดอักขระที่แยกอาร์กิวเมนต์ในวัตถุ delimiter |
| [getEndingCharacter()](#getEndingCharacter--) | ตัวอักษรสิ้นสุดของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดสิ้นสุดหรือปิด |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | ตัวอักษรสิ้นสุดของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดสิ้นสุดหรือปิด |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true delimiter จะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของ operand |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true delimiter จะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของ operand |
| [getDelimiterShape()](#getDelimiterShape--) | ระบุรูปแบบของ delimiter ในวัตถุ delimiter |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | ระบุรูปแบบของ delimiter ในวัตถุ delimiter |
| [delimit(char separatorCharacter)](#delimit-char-) | แยกอาร์กิวเมนต์โดยใช้ตัวอักษร delimiter ที่ระบุ |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่แยกด้วยอักขระ delimiter

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

ตัวอักษรเริ่มต้นของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบ เช่น วงเล็บ, วงห่วง, และปีกกา. ค่าตั้งต้น: '('.

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

ตัวอักษรเริ่มต้นของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดเริ่มต้นหรือเปิด. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบ เช่น วงเล็บ, วงห่วง, และปีกกา. ค่าตั้งต้น: '('.

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
public abstract char getSeparatorCharacter()
```

ตัวอักษรตัวคั่นของ Delimiter กำหนดอักขระที่แยกอาร์กิวเมนต์ในวัตถุ delimiter. ค่าเริ่มต้น: '|'.

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

ตัวอักษรตัวคั่นของ Delimiter กำหนดอักขระที่แยกอาร์กิวเมนต์ในวัตถุ delimiter. ค่าเริ่มต้น: '|'.

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
public abstract char getEndingCharacter()
```

ตัวอักษรสิ้นสุดของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดสิ้นสุดหรือปิด. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบ เช่น วงเล็บ, วงห่วง, และปีกกา. ค่าตั้งต้น: ')'.

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

ตัวอักษรสิ้นสุดของ Delimiter กำหนดอักขระ delimiter ที่เป็นจุดสิ้นสุดหรือปิด. Delimiter ทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบ เช่น วงเล็บ, วงห่วง, และปีกกา. ค่าตั้งต้น: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true delimiter จะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของ operand. ค่าเริ่มต้นคือ true

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

ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็น true delimiter จะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของ operand. ค่าเริ่มต้นคือ true

--------------------

> ```
> Example:
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
public abstract int getDelimiterShape()
```

ระบุรูปแบบของ delimiter ในวัตถุ delimiter. เมื่อเป็น MathDelimiterShape.Centered delimiter จะอยู่ตรงกลางแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา. เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปแบบของพวกมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

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

ระบุรูปแบบของ delimiter ในวัตถุ delimiter. เมื่อเป็น MathDelimiterShape.Centered delimiter จะอยู่ตรงกลางแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา. เมื่อเป็น MathDelimiterShape.Match ความสูงและรูปแบบของพวกมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

แยกอาร์กิวเมนต์โดยใช้ตัวอักษร delimiter ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char | ตัวอักษร delimiter |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - วัตถุนี้หลังจากใช้ตัวอักษร delimiter