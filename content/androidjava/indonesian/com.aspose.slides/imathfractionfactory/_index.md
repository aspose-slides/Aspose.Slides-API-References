---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Memungkinkan membuat pecahan matematika
type: docs
url: /id/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Memungkinkan membuat pecahan matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Membuat sebuah pecahan matematika |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat sebuah pecahan matematika |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Membuat sebuah pecahan matematika

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Tipe pecahan |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Pecahan matematika baru [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Membuat sebuah pecahan matematika

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Pecahan matematika baru [IMathFraction](../../com.aspose.slides/imathfraction)