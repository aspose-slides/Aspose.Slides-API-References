---
title: MathFractionFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | إنشاء كسر رياضي |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | إنشاء كسر رياضي |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


إنشاء كسر رياضي

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر |

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


إنشاء كسر رياضي

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

**القيمة المرجعة:**
[IMathFraction](../../com.aspose.slides/imathfraction) - كسر رياضي جديد