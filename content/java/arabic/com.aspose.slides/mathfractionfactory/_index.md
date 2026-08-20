---
title: MathFractionFactory
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يسمح بإنشاء كسر رياضي
type: docs
url: /ar/com.aspose.slides/mathfractionfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

يسمح بإنشاء كسر رياضي

--------------------

للتوافق مع COM
## المنشئون

| المُنشئ | الوصف |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | ينشئ كسرًا رياضيًا |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ كسرًا رياضيًا |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```

### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

ينشئ كسرًا رياضيًا

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

ينشئ كسرًا رياضيًا

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

**الإرجاع:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد