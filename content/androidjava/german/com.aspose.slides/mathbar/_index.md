---
title: MathBar
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Überstrich oder Unterstrich
type: docs
url: /de/com.aspose.slides/mathbar/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Überstrich oder Unterstrich

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Initialisiert MathBar mit Überstrich (Top position) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Initialisiert MathBar mit angegebener Position |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getPosition()](#getPosition--) | Position der Balkenlinie. |
| [setPosition(int value)](#setPosition-int-) | Position der Balkenlinie. |
| [getChildren()](#getChildren--) | Gibt Kind-Elemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


Initialisiert MathBar mit Überstrich (Top position)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basis-Element, auf das der Balken angewendet wird |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


Initialisiert MathBar mit angegebener Position

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basis-Element, auf das der Balken angewendet wird |
| position | int | Position der Balkenlinie. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Position der Balkenlinie. Standard: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Rückgabewert:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Position der Balkenlinie. Standard: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gibt Kind-Elemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps