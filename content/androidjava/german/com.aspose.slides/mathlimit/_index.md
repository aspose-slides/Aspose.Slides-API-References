---
title: MathLimit
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Limit-Objekt an, das aus Text auf der Grundlinie und verkleinertem Text unmittelbar darüber oder darunter besteht.
type: docs
url: /de/com.aspose.slides/mathlimit/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathLimit](../../com.aspose.slides/imathlimit), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathLimit extends MathElementBase implements IMathLimit, IHasControlCharacterProperties
```

Gibt das Limit-Objekt an, das aus Text auf der Grundlinie und verkleinertem Text unmittelbar darüber oder darunter besteht.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Initialisiert eine neue Instanz der MathLimit-Klasse. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathLimit-Klasse mit unterer Grenze |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getLimit()](#getLimit--) | Grenzargument |
| [getUpperLimit()](#getUpperLimit--) | Gibt an, ob es sich um eine obere oder untere Grenze handelt |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Gibt an, ob es sich um eine obere oder untere Grenze handelt |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Initialisiert eine neue Instanz der MathLimit-Klasse.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"), false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | boolean |  |

### MathLimit(IMathElement baseArg, IMathElement limit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLimit(IMathElement baseArg, IMathElement limit)
```


Initialisiert eine neue Instanz der MathLimit-Klasse mit unterer Grenze

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public final IMathElement getLimit()
```


Grenzargument

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


Gibt an, ob es sich um eine obere oder untere Grenze handelt

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**Rückgabe:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


Gibt an, ob es sich um eine obere oder untere Grenze handelt

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gibt Kindelemente zurück

**Rückgabe:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Steuerzeichen-Eigenschaften

**Rückgabe:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps