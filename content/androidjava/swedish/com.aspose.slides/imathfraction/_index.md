---
title: IMathFraction
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar bråkobjektet som består av en täljare och en nämnare separerade av ett bråkstreck.
type: docs
url: /sv/com.aspose.slides/imathfraction/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Specificerar bråkobjektet, som består av en täljare och en nämnare separerade av ett bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkegenskaperna. Bråkobjektet används också för att representera stackfunktionen, som placerar ett element ovanför ett annat, utan bråkstreck.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFractionType()](#getFractionType--) | Bråktyp Standard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Bråktyp Standard: Bar |
| [getNumerator()](#getNumerator--) | Täljare |
| [getDenominator()](#getDenominator--) | Nämnare |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Bråktyp Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
```

**Returnerar:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

Bråktyp Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```

Täljare

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```

Nämnare

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)