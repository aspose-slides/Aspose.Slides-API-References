---
title: MathFraction
second_title: Aspose.Slides pro Java - reference API
description: Definuje objekt zlomek, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou.
type: docs
url: /cs/com.aspose.slides/mathfraction/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Definuje objekt zlomek, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou. Zlomková čára může být vodorovná nebo úhlopříčná, v závislosti na vlastnostech zlomku. Objekt zlomek se také používá k reprezentaci funkce zásobníku, která umisťuje jeden prvek nad druhý bez zlomkové čáry.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Inicializuje MathFraction s určeným čitatelem, jmenovatelem a typem |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializuje MathFraction typu 'Bar' s určeným čitatelem a jmenovatelem |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFractionType()](#getFractionType--) | Typ zlomku Výchozí: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Typ zlomku Výchozí: Bar |
| [getNumerator()](#getNumerator--) | Čitatel |
| [getDenominator()](#getDenominator--) | Jmenovatel |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Inicializuje MathFraction s určeným čitatelem, jmenovatelem a typem

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |
| fractionType | int | Typ zlomku |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

Inicializuje MathFraction typu 'Bar' s určeným čitatelem a jmenovatelem

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Čitatel |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Jmenovatel |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
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
public final void setFractionType(int value)
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
public final IMathElement getNumerator()
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
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získat podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídícího znaku

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps