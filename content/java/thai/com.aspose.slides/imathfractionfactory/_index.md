---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math fraction
type: docs
url: /th/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

อนุญาตให้สร้างเศษคณิต

--------------------

สำหรับการเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | สร้างเศษคณิต |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างเศษคณิต |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


สร้างเศษคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |
| fractionType | int | ประเภทเศษคณิต |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษคณิตใหม่ [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


สร้างเศษคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษคณิตใหม่ [IMathFraction](../../com.aspose.slides/imathfraction)