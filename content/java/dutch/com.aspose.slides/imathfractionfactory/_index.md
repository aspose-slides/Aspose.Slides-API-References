---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API-referentie
description: Maakt een wiskundige breuk
type: docs
url: /nl/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Maakt een wiskundige breuk

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Maakt een wiskundige breuk |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Maakt een wiskundige breuk |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Maakt een wiskundige breuk

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Teller |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |
| fractionType | int | Type breuk |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nieuwe wiskundige breuk [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Maakt een wiskundige breuk

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Teller |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nieuwe wiskundige breuk [IMathFraction](../../com.aspose.slides/imathfraction)