---
title: MathLimit
second_title: Aspose.Slides für Java API Referenz
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
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Initialisiert eine neue Instanz der Klasse MathLimit. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der Klasse MathLimit mit unterer Grenze |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getLimit()](#getLimit--) | Grenzargument |
| [getUpperLimit()](#getUpperLimit--) | Gibt oberen oder unteren Grenzwert an |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Gibt oberen oder unteren Grenzwert an |
| [getChildren()](#getChildren--) | Gibt Kind-Elemente zurück |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Initialisiert eine neue Instanz der Klasse MathLimit.

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


Initialisiert eine neue Instanz der Klasse MathLimit mit unterer Grenze

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

**Rückgabewert:**
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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


Gibt oberen oder unteren Grenzwert an

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**Rückgabewert:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


Gibt oberen oder unteren Grenzwert an

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