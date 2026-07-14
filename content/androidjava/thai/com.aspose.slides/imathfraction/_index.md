---
title: IMathFraction
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุอ็อบเจกต์ส่วนเศษซึ่งประกอบด้วยตัวเศษและตัวส่วนที่คั่นด้วยเส้นส่วนเศษ
type: docs
url: /th/com.aspose.slides/imathfraction/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

ระบุอ็อบเจกต์ส่วนเศษ ซึ่งประกอบด้วยตัวเศษและตัวส่วนที่คั่นด้วยเส้นส่วนเศษ เส้นส่วนเศษอาจเป็นแนวนอนหรือแนวทแยง ตามคุณสมบัติของส่วนเศษ อ็อบเจกต์ส่วนเศษยังใช้เพื่อแสดงฟังก์ชันสแต็ก ที่วางองค์ประกอบหนึ่งไว้บนอีกองค์ประกอบหนึ่งโดยไม่มีเส้นส่วนเศษ

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type ค่าเริ่มต้น: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type ค่าเริ่มต้น: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Fraction type ค่าเริ่มต้น: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**คืนค่า:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Fraction type ค่าเริ่มต้น: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Numerator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)