---
title: MathFractionFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างเศษคณิต
type: docs
url: /th/com.aspose.slides/mathfractionfactory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซทั้งหมดที่ทำการใช้งาน:**  
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)  
```
public class MathFractionFactory implements IMathFractionFactory
```

อนุญาตให้สร้างเศษคณิต

--------------------

สำหรับความเข้ากันได้กับ COM
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | สร้างเศษคณิต |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างเศษคณิต |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```

### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

สร้างเศษคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |
| fractionType | int | ประเภทเศษ |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษคณิตใหม่
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

สร้างเศษคณิต

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษคณิตใหม่