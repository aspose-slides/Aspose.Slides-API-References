---
title: MathFractionFactory
second_title: Aspose.Slides für Android über Java API Referenz
description: Ermöglicht das Erstellen eines mathematischen Bruchs
type: docs
url: /de/com.aspose.slides/mathfractionfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Ermöglicht das Erstellen eines mathematischen Bruchs

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Erstellt einen mathematischen Bruch |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Bruch |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Erstellt einen mathematischen Bruch

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |
| fractionType | int | Bruchtyp |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer mathematischer Bruch
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Erstellt einen mathematischen Bruch

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |

**Rückgabewert:**
[IMathFraction](../../com.aspose.slides/imathfraction) - neuer mathematischer Bruch