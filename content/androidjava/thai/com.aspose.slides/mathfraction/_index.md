---
title: MathFraction
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุวัตถุเศษส่วนที่ประกอบด้วยตัวเศษและตัวส่วนที่คั่นด้วยเส้นแบ่งเศษส่วน.
type: docs
url: /th/com.aspose.slides/mathfraction/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

กำหนดวัตถุเศษส่วน ซึ่งประกอบด้วยตัวเศษและตัวส่วนที่คั่นด้วยเส้นแบ่งเศษส่วน เส้นแบ่งสามารถเป็นแนวนอนหรือแนวทแยงมุม ขึ้นอยู่กับคุณสมบัติของเศษส่วน วัตถุเศษส่วนยังใช้เพื่อแสดงฟังก์ชันสแต็กที่วางองค์ประกอบหนึ่งเหนืออีกองค์ประกอบหนึ่งโดยไม่มีเส้นแบ่งเศษส่วน

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | เริ่มต้น MathFraction ด้วยตัวเศษ ตัวส่วน และประเภทที่ระบุ |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้น MathFraction ของประเภท 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFractionType()](#getFractionType--) | ประเภทของเศษส่วน ค่าเริ่มต้น: Bar |
| [setFractionType(int value)](#setFractionType-int-) | ประเภทของเศษส่วน ค่าเริ่มต้น: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
| [getChildren()](#getChildren--) | รับองค์ประกอบย่อย |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |

### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

เริ่มต้น MathFraction ด้วยตัวเศษ ตัวส่วน และประเภทที่ระบุ

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | ประเภทของเศษส่วน |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

เริ่มต้น MathFraction ของประเภท 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

ประเภทของเศษส่วน ค่าเริ่มต้น: Bar

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
public final void setFractionType(int value)
```

ประเภทของเศษส่วน ค่าเริ่มต้น: Bar

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
public final IMathElement getNumerator()
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
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบย่อย

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps