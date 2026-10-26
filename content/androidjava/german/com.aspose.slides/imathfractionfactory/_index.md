---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math fraction
type: docs
url: /de/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Ermöglicht das Erstellen eines mathematischen Bruchs

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Erstellt einen mathematischen Bruch |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Bruch |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Erstellt einen mathematischen Bruch

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |
| fractionType | int | Bruchtyp |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Neuer mathematischer Bruch [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Erstellt einen mathematischen Bruch

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Neuer mathematischer Bruch [IMathFraction](../../com.aspose.slides/imathfraction)