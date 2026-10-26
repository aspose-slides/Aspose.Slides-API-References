---
title: MathFractionFactory
second_title: مرجع API Aspose.Slides برای Java
description: امکان ایجاد یک کسر ریاضی را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/mathfractionfactory/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

اجازۀ ایجاد یک کسر ریاضی

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## متدها

| متد | توضیح |
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


یک کسر ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |
| fractionType | int | نوع کسر |

**مقدار بازگشت:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر ریاضی جدید
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


یک کسر ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |

**مقدار بازگشت:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر ریاضی جدید