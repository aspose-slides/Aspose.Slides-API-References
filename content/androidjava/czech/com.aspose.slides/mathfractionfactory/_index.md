---
title: MathFractionFactory
second_title: Aspose.Slides pro Android – reference Java API
description: Umožňuje vytvořit matematický zlomek
type: docs
url: /cs/com.aspose.slides/mathfractionfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Umožňuje vytvořit matematický zlomek

--------------------

Pro kompatibilitu s COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Vytváří matematický zlomek |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytváří matematický zlomek |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Vytváří matematický zlomek

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |
| fractionType | int | Typ zlomku |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new math fraction
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Vytváří matematický zlomek

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new math fraction