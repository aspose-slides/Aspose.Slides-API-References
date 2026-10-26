---
title: MathFraction
second_title: Aspose.Slides för Java API-referens
description: Anger bråkobjektet som består av en täljare och en nämnare separerade av ett bråkstreck.
type: docs
url: /sv/com.aspose.slides/mathfraction/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Anger bråkobjektet, som består av en täljare och en nämnare separerade av ett bråkstreck. Bråkstrecket kan vara horisontellt eller diagonal, beroende på bråkegenskaperna. Bråkobjektet används också för att representera stapelfunktionen, som placerar ett element ovanpå ett annat, utan bråkstreck.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initierar MathFraction med den angivna täljaren, nämnaren och typen |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initierar en MathFraction av typen 'Bar' med den angivna täljaren och nämnaren |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFractionType()](#getFractionType--) | Bråktyp Standard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Bråktyp Standard: Bar |
| [getNumerator()](#getNumerator--) | Täljare |
| [getDenominator()](#getDenominator--) | Nämnare |
| [getChildren()](#getChildren--) | Hämta underordnade element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrollteckenegenskaper |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Initierar MathFraction med den angivna täljaren, nämnaren och typen

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Täljare |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |
| fractionType | int | Bråktyp |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Initierar en MathFraction av typen 'Bar' med den angivna täljaren och nämnaren

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Täljare |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nämnare |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Bråktyp Standard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Returnerar:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
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
public final IMathElement getNumerator()
```


Täljare

--------------------

> ```
> Exempel:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Hämtar underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrollteckenegenskaper

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps