---
title: MathFraction
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het breukobject dat bestaat uit een teller en een noemer, gescheiden door een breukstreep.
type: docs
url: /nl/com.aspose.slides/mathfraction/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Specificeert het breukobject, bestaande uit een teller en een noemer die gescheiden zijn door een breukstreep. De breukstreep kan horizontaal of diagonaal zijn, afhankelijk van de breukeigenschappen. Het breukobject wordt ook gebruikt om de stapelfunctie te representeren, waarbij één element boven een ander wordt geplaatst, zonder breukstreep.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initialiseert MathFraction met de opgegeven teller, noemer en type |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een MathFraction van type 'Bar' met de opgegeven teller en noemer |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getFractionType()](#getFractionType--) | Type breuk Standaard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Type breuk Standaard: Bar |
| [getNumerator()](#getNumerator--) | Teller |
| [getDenominator()](#getDenominator--) | Noemer |
| [getChildren()](#getChildren--) | Haal onderliggende elementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Controlcharactereigenschappen |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Initialiseert MathFraction met de opgegeven teller, noemer en type

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Teller |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |
| fractionType | int | Type breuk |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Initialiseert een MathFraction van type 'Bar' met de opgegeven teller en noemer

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Teller |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Noemer |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Type breuk Standaard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Retour:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Type breuk Standaard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Teller

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Noemer

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal onderliggende elementen op

**Retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Controlcharactereigenschappen

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps