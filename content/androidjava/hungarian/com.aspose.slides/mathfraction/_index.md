---
title: MathFraction
second_title: Aspose.Slides Android-hoz Java API referenciája
description: Megadja a tört objektumot, amely egy számlálóval és egy nevezővel rendelkezik, és egy törtvonallal van elválasztva.
type: docs
url: /hu/com.aspose.slides/mathfraction/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Meghatározza a tört objektumot, amely számlálóval és nevezővel rendelkezik, és egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet a másik fölé helyez, törtvonal nélkül.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Inicializálja a MathFraction-t a megadott számlálóval, nevezővel és típussal |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializál egy 'Bar' típusú MathFraction-t a megadott számlálóval és nevezővel |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFractionType()](#getFractionType--) | A tört típusa alapértelmezett: Bar |
| [setFractionType(int value)](#setFractionType-int-) | A tört típusa alapértelmezett: Bar |
| [getNumerator()](#getNumerator--) | Számláló |
| [getDenominator()](#getDenominator--) | Nevező |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |

### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Inicializálja a MathFraction-t a megadott számlálóval, nevezővel és típussal.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |
| fractionType | int | Tört típusa |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

Inicializál egy 'Bar' típusú MathFraction-t a megadott számlálóval és nevezővel.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Számláló |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Nevező |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```

A tört típusa alapértelmezett: Bar

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
public final void setFractionType(int value)
```

A tört típusa alapértelmezett: Bar

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
public final IMathElement getNumerator()
```

Számláló

--------------------

> ```
> Példa:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps