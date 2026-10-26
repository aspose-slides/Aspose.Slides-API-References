---
title: IMathFraction
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje objekt zlomku skládající se z čitatele a jmenovatele oddělených zlomkovou čarou.
type: docs
url: /cs/com.aspose.slides/imathfraction/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou. Zlomková čára může být vodorovná nebo šikmá, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce stack, která umisťuje jeden prvek nad druhý, bez zlomkové čáry.

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
| [getFractionType()](#getFractionType--) | Fraction typ Výchozí: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction typ Výchozí: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Fraction typ Výchozí: Bar

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

Fraction typ Výchozí: Bar

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

Numerator

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

Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)