---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Matematik kesir oluşturmanıza olanak tanır
type: docs
url: /tr/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Matematik kesir oluşturmanıza olanak tanır

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Bir matematik kesir oluşturur |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Bir matematik kesir oluşturur |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Bir matematik kesir oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir tipi |

**Dönüş:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Yeni matematik kesir [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Bir matematik kesir oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Dönüş:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Yeni matematik kesir [IMathFraction](../../com.aspose.slides/imathfraction)