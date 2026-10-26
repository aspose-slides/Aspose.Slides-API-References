---
title: MathFractionFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: อนุญาตให้สร้างเศษส่วนคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathfractionfactory/
---
**Inheritance:**  
การสืบทอด:

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

อนุญาตให้สร้างเศษส่วนคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## เมธอด

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Creates a math fraction

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type |

**ค่าที่คืน:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนคณิตศาสตร์ใหม่
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Creates a math fraction

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

**ค่าที่คืน:**
[IMathFraction](../../com.aspose.slides/imathfraction) - เศษส่วนคณิตศาสตร์ใหม่