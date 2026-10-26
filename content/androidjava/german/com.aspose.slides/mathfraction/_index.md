---
title: MathFraction
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Fraction-Objekt an, das aus einem Zähler und einem Nenner besteht, die durch einen Bruchstrich getrennt sind.
type: docs
url: /de/com.aspose.slides/mathfraction/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Gibt das Fraction-Objekt an, das aus einem Zähler und einem Nenner besteht, die durch einen Bruchstrich getrennt sind. Der Bruchstrich kann horizontal oder diagonal sein, abhängig von den Fraction-Eigenschaften. Das Fraction-Objekt wird auch verwendet, um die Stapelfunktion darzustellen, bei der ein Element über einem anderen platziert wird, ohne einen Bruchstrich.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initialisiert MathFraction mit dem angegebenen Zähler, Nenner und Typ |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert ein MathFraction vom Typ 'Bar' mit dem angegebenen Zähler und Nenner |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction-Typ Standard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction-Typ Standard: Bar |
| [getNumerator()](#getNumerator--) | Zähler |
| [getDenominator()](#getDenominator--) | Nenner |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Initialisiert MathFraction mit dem angegebenen Zähler, Nenner und Typ

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |
| fractionType | int | Fraction-Typ |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

Initialisiert ein MathFraction vom Typ 'Bar' mit dem angegebenen Zähler und Nenner

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Zähler |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nenner |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

Fraction-Typ Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Rückgabewert:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```

Fraction-Typ Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```

Zähler

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```

Nenner

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt Kindelemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps