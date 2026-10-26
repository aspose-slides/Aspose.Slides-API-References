---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math fraction
type: docs
url: /fa/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

اجاز می‌دهد یک کسر ریاضی ایجاد کند

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | یک کسر ریاضی ایجاد می‌کند |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک کسر ریاضی ایجاد می‌کند |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

یک کسر ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |
| fractionType | int | نوع کسر |

**بازگشت:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر ریاضی جدید [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

یک کسر ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |

**بازگشت:**
[IMathFraction](../../com.aspose.slides/imathfraction) - کسر ریاضی جدید [IMathFraction](../../com.aspose.slides/imathfraction)