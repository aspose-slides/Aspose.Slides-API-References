---
title: MathFractionFactory
second_title: Aspose.Slides pro Java - referenční příručka API
description: Umožňuje vytvořit matematický zlomek
type: docs
url: /cs/com.aspose.slides/mathfractionfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Umožňuje vytvořit matematický zlomek

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Vytvoří matematický zlomek |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří matematický zlomek |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Vytvoří matematický zlomek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |
| fractionType | int | Typ zlomku |

**Návratová hodnota:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový matematický zlomek
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Vytvoří matematický zlomek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |

**Návratová hodnota:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nový matematický zlomek