---
title: IMathFraction
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Bruchobjekt an, das aus einem Zähler und einem Nenner besteht, die durch einen Bruchstrich getrennt sind.
type: docs
url: /de/com.aspose.slides/imathfraction/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Speziﬁziert das Bruchobjekt, das aus einem Zähler und einem Nenner besteht, die durch einen Bruchstrich getrennt sind. Der Bruchstrich kann horizontal oder diagonal sein, abhängig von den Bruch-Eigenschaften. Das Bruchobjekt wird außerdem verwendet, um die Stapelfunktion darzustellen, die ein Element über ein anderes legt, ohne Bruchstrich.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type Default: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Fraction type Default: Bar

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
public abstract void setFractionType(int value)
```

Fraction type Default: Bar

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
public abstract IMathElement getNumerator()
```

Numerator

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
public abstract IMathElement getDenominator()
```

Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)