---
title: IMathFraction
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji Java API
description: Określa obiekt ułamka składający się z licznika i mianownika oddzielonych kreską ułamkową.
type: docs
url: /pl/com.aspose.slides/imathfraction/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getFractionType()](#getFractionType--) | Typ ułamka Domyślnie: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Typ ułamka Domyślnie: Bar |
| [getNumerator()](#getNumerator--) | Licznik |
| [getDenominator()](#getDenominator--) | Mianownik |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Typ ułamka Domyślnie: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Zwraca:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Typ ułamka Domyślnie: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Licznik

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Mianownik

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)