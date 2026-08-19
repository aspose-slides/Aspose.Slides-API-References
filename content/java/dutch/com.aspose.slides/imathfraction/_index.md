---
title: IMathFraction
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert het fractie-object dat bestaat uit een teller en een noemer, gescheiden door een breukstreep.
type: docs
url: /nl/com.aspose.slides/imathfraction/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Specificeert het fractie-object, bestaande uit een teller en noemer gescheiden door een breukstreep. De breukstreep kan horizontaal of diagonaal zijn, afhankelijk van de fractie-eigenschappen. Het fractie-object wordt ook gebruikt om de stapelfunctie weer te geven, die één element boven een ander plaatst, zonder breukstreep.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fractietype Standaard: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fractietype Standaard: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Fractietype Standaard: Bar

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
public abstract void setFractionType(int value)
```


Fractietype Standaard: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```


**Parameters:**
| Parameter | Type | Description |
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

**Retourwaarde:**
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

**Retourwaarde:**
[IMathElement](../../com.aspose.slides/imathelement)