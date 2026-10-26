---
title: IMathFraction
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุวัตถุเศษส่วนที่ประกอบด้วยตัวเศษและส่วนที่แยกโดยแถบเศษส่วน
type: docs
url: /th/com.aspose.slides/imathfraction/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

กำหนดวัตถุเศษส่วน ซึ่งประกอบด้วยตัวเศษและส่วนที่แยกโดยแถบเศษส่วน แถบเศษส่วนอาจเป็นแนวนอนหรือแนวทแยงตามคุณสมบัติของเศษส่วน วัตถุเศษส่วนยังใช้เพื่อแสดงฟังก์ชันสแต็ก ซึ่งวางองค์ประกอบหนึ่งเหนืออีกองค์ประกอบหนึ่งโดยไม่มีแถบเศษส่วน.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFractionType()](#getFractionType--) | ประเภทเศษส่วน ค่าเริ่มต้น: Bar |
| [setFractionType(int value)](#setFractionType-int-) | ประเภทเศษส่วน ค่าเริ่มต้น: Bar |
| [getNumerator()](#getNumerator--) | ตัวเศษ |
| [getDenominator()](#getDenominator--) | ส่วน |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


ประเภทเศษส่วน ค่าเริ่มต้น: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
```

**คืนค่า:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


ประเภทเศษส่วน ค่าเริ่มต้น: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


ตัวเศษ

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


ส่วน

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)