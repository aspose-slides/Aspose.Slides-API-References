---
title: MathFractionFactory
second_title: Java API Referansı üzerinden Aspose.Slides for Android
description: Matematik kesri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathfractionfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Matematik kesri oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Matematik kesri oluşturur |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Matematik kesri oluşturur |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Matematik kesri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir türü |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni matematik kesri
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Matematik kesri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Döndürür:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni matematik kesri