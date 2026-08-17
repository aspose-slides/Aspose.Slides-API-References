---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Matematik kesir oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Matematik kesir oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Matematik kesir oluşturur |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Matematik kesir oluşturur |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Matematik kesir oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir tipi |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Yeni matematik kesir [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Matematik kesir oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Yeni matematik kesir [IMathFraction](../../com.aspose.slides/imathfraction)