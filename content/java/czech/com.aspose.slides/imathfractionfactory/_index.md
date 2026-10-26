---
title: IMathFractionFactory
second_title: Aspose.Slides for Java – referenční příručka API
description: Umožňuje vytvořit matematický zlomek
type: docs
url: /cs/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Umožňuje vytvořit matematický zlomek

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Vytvoří matematický zlomek |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří matematický zlomek |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Vytvoří matematický zlomek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |
| fractionType | int | Typ zlomku |

**Návratová hodnota:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nový matematický zlomek [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Vytvoří matematický zlomek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |

**Návratová hodnota:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nový matematický zlomek [IMathFraction](../../com.aspose.slides/imathfraction)