---
title: IMathFractionFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API لـ Java
description: يسمح بإنشاء كسر رياضي
type: docs
url: /ar/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

يسمح بإنشاء كسر رياضي

--------------------

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | ينشئ كسرًا رياضيًا |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ كسرًا رياضيًا |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

ينشئ كسرًا رياضيًا

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر |

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

ينشئ كسرًا رياضيًا

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد [IMathFraction](../../com.aspose.slides/imathfraction)