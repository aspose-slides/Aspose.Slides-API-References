---
title: MathFraction
second_title: Aspose.Slides voor Java API Referentie
description: Specificeert het breukobject dat bestaat uit een teller en een noemer gescheiden door een breukstreep.
type: docs
url: /nl/com.aspose.slides/mathfraction/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Specificeert het breukobject, bestaande uit een teller en een noemer die gescheiden zijn door een breukstreep. De breukstreep kan horizontaal of diagonaal zijn, afhankelijk van de breuk-eigenschappen. Het breukobject wordt tevens gebruikt om de stapelfunctie weer te geven, die één element boven een ander plaatst, zonder breukstreep.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Initialiseert MathFraction met de opgegeven teller, noemer en type |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een MathFraction van type 'Bar' met de opgegeven teller en noemer |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFractionType()](#getFractionType--) | Breuktype Standaard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Breuktype Standaard: Bar |
| [getNumerator()](#getNumerator--) | Teller |
| [getDenominator()](#getDenominator--) | Noemer |
| [getChildren()](#getChildren--) | Haal onderliggende elementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
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
| fractionType | int | Breuktype |

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


Breuktype Standaard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Retourwaarde:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Breuktype Standaard: Bar

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

**Retourwaarde:**
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

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal onderliggende elementen op

**Retourwaarde:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Retourwaarde:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps