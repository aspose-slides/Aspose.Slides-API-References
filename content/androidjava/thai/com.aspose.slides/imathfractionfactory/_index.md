---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math fraction
type: docs
url: /th/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

อนุญาตให้สร้างเศษส่วนคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | สร้างส่วนคณิตศาสตร์ |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างส่วนคณิตศาสตร์ |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


สร้างส่วนคณิตศาสตร์

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |
| fractionType | int | ประเภทส่วน |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - ส่วนคณิตศาสตร์ใหม่ [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


สร้างส่วนคณิตศาสตร์

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวเศษ |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | ตัวส่วน |

**ผลลัพธ์:**
[IMathFraction](../../com.aspose.slides/imathfraction) - ส่วนคณิตศาสตร์ใหม่ [IMathFraction](../../com.aspose.slides/imathfraction)