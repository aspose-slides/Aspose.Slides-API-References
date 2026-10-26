---
title: MathFraction
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Określa obiekt ułamka składający się z licznika i mianownika oddzielonych kreską ułamkową.
type: docs
url: /pl/com.aspose.slides/mathfraction/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub ukośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Inicjalizuje MathFraction z określonym licznikiem, mianownikiem i typem |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje MathFraction typu 'Bar' z określonym licznikiem i mianownikiem |
## Metody

| Metoda | Opis |
| --- | --- |
| [getFractionType()](#getFractionType--) | Typ ułamka Domyślnie: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Typ ułamka Domyślnie: Bar |
| [getNumerator()](#getNumerator--) | Licznik |
| [getDenominator()](#getDenominator--) | Mianownik |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Inicjalizuje MathFraction z określonym licznikiem, mianownikiem i typem

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Type | Opis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Licznik |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |
| fractionType | int | Typ ułamka |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Inicjalizuje MathFraction typu 'Bar' z określonym licznikiem i mianownikiem

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parametry:**
| Parametr | Type | Opis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Licznik |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
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
public final void setFractionType(int value)
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
| Parametr | Type | Opis |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
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
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps