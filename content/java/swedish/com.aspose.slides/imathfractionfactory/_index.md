---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math fraction
type: docs
url: /sv/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Tillåter att skapa ett matematiskt bråk

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Skapar ett matematiskt bråk |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar ett matematiskt bråk |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Skapar ett matematiskt bråk

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Täljare |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |
| fractionType | int | Fraktionstyp |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nytt matematiskt bråk [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Skapar ett matematiskt bråk

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Täljare |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |

**Returnerar:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nytt matematiskt bråk [IMathFraction](../../com.aspose.slides/imathfraction)