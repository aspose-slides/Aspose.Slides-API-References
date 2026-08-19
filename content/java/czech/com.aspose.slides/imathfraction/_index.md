---
title: IMathFraction
second_title: Aspose.Slides pro Java API Reference
description: Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených čárou zlomku.
type: docs
url: /cs/com.aspose.slides/imathfraction/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených čárou zlomku. Čára zlomku může být vodorovná nebo diagonální, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce stack, která umisťuje jeden prvek nad druhý bez čáry zlomku.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getFractionType()](#getFractionType--) | Typ zlomku Výchozí: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Typ zlomku Výchozí: Bar |
| [getNumerator()](#getNumerator--) | Čitatel |
| [getDenominator()](#getDenominator--) | Jmenovatel |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Typ zlomku Výchozí: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Vrací:**  
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Typ zlomku Výchozí: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Čitatel

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Vrací:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Jmenovatel

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Vrací:**  
[IMathElement](../../com.aspose.slides/imathelement)