---
title: MathFraction
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุอ็อบเจ็กต์ส่วนเศษที่ประกอบด้วยตัวเศษและตัวส่วนโดยคั่นด้วยบาร์ส่วนเศษ.
type: docs
url: /th/com.aspose.slides/mathfraction/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

ระบุอ็อบเจ็กต์ส่วนเศษที่ประกอบด้วยตัวเศษและตัวส่วนโดยคั่นด้วยบาร์ส่วนเศษ. บาร์ส่วนเศษสามารถเป็นแนวนอนหรือแนวทแยงตามคุณสมบัติของส่วนเศษ. อ็อบเจ็กต์ส่วนเศษยังใช้เพื่อแสดงฟังก์ชันสแต็กที่วางอิลิเมนต์หนึ่งเหนืออีกอิลิเมนต์หนึ่งโดยไม่มีบาร์ส่วนเศษ.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | เริ่มต้น MathFraction ด้วยตัวเศษ ตัวส่วน และประเภทที่ระบุ |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้น MathFraction ประเภท 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFractionType()](#getFractionType--) | ประเภทส่วนเศษ ค่าเริ่มต้น: Bar |
| [setFractionType(int value)](#setFractionType-int-) | ประเภทส่วนเศษ ค่าเริ่มต้น: Bar |
| [getNumerator()](#getNumerator--) | ตัวเศษ |
| [getDenominator()](#getDenominator--) | ตัวส่วน |
| [getChildren()](#getChildren--) | รับอิลิเมนต์ลูก |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |
| fractionType | int | ประเภทส่วนเศษ |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

เริ่มต้น MathFraction ประเภท 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

ประเภทส่วนเศษ ค่าเริ่มต้น: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**ค่าที่คืน:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```

ประเภทส่วนเศษ ค่าเริ่มต้น: Bar

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
public final IMathElement getNumerator()
```

ตัวเศษ

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**ค่าที่คืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```

ตัวส่วน

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**ค่าที่คืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับอิลิเมนต์ลูก

**ค่าที่คืน:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่คืน:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps