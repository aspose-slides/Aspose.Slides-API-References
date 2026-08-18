---
title: MathFractionFactory
second_title: Aspose.Slides for Java API Referansı
description: Matematik kesri oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathfractionfactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
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
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Bir matematik kesri oluşturur |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Bir matematik kesri oluşturur |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```

### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Bir matematik kesri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |
| fractionType | int | Kesir tipi |

**Dönüş Değeri:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni matematik kesri
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Bir matematik kesri oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pay |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Payda |

**Dönüş Değeri:**
[IMathFraction](../../com.aspose.slides/imathfraction) - yeni matematik kesri