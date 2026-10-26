---
title: IMathFractionFactory
second_title: Aspose.Slides for Java Referensi API
description: Mengizinkan membuat sebuah pecahan matematika
type: docs
url: /id/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Mengizinkan membuat sebuah pecahan matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Membuat sebuah pecahan matematika |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat sebuah pecahan matematika |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Membuat sebuah pecahan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pembilang |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |
| fractionType | int | Tipe pecahan |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Pecahan matematika baru [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Membuat sebuah pecahan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pembilang |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |

**Mengembalikan:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Pecahan matematika baru [IMathFraction](../../com.aspose.slides/imathfraction)