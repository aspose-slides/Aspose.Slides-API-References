---
title: IMathFraction
second_title: Aspose.Slides für Java API-Referenz
description: Gibt das Bruchobjekt an, das aus einem Zähler und einem Nenner besteht, getrennt durch einen Bruchstrich.
type: docs
url: /de/com.aspose.slides/imathfraction/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Gibt das Bruchobjekt an, das aus einem Zähler und einem Nenner besteht, getrennt durch einen Bruchstrich. Der Bruchstrich kann horizontal oder diagonal sein, abhängig von den Bruch-Eigenschaften. Das Bruchobjekt wird auch verwendet, um die Stapelfunktion darzustellen, die ein Element über einem anderen platziert, ohne Bruchstrich.

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
| [getFractionType()](#getFractionType--) | Fraktionstyp Standard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraktionstyp Standard: Bar |
| [getNumerator()](#getNumerator--) | Zähler |
| [getDenominator()](#getDenominator--) | Nenner |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Fraktionstyp Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Rückgabe:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

Fraktionstyp Standard: Bar

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

Zähler

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```

Nenner

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)