---
title: IMathFraction
second_title: Aspose.Slides Androidra a Java API hivatkozásból
description: Meghatározza a tört objektumot, amely számlálóból és nevezőből áll, és egy törtvonal választja el őket.
type: docs
url: /hu/com.aspose.slides/imathfraction/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Meghatározza a tört objektumot, amely számlálóból és nevezőből áll, és egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet egy másik fölé helyez, törtvonal nélkül.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Metódusok

| Method | Leírás |
| --- | --- |
| [getFractionType()](#getFractionType--) | A tört típusa Alapértelmezett: Bar |
| [setFractionType(int value)](#setFractionType-int-) | A tört típusa Alapértelmezett: Bar |
| [getNumerator()](#getNumerator--) | Számláló |
| [getDenominator()](#getDenominator--) | Nevező |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


A tört típusa Alapértelmezett: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Visszatérési érték:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


A tört típusa Alapértelmezett: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Számláló

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Nevező

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)