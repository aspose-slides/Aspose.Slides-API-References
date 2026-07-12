---
title: IMathLimit
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Limit-Objekt an, das aus Text auf der Grundlinie und verkleinertem Text unmittelbar darüber oder darunter besteht.
type: docs
url: /de/com.aspose.slides/imathlimit/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Gibt das Limit-Objekt an, das aus Text auf der Grundlinie und verkleinertem Text unmittelbar darüber oder darunter besteht.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getLimit()](#getLimit--) | Limit-Argument |
| [getUpperLimit()](#getUpperLimit--) | Gibt obere oder untere Grenze an |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Gibt obere oder untere Grenze an |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


Limit-Argument

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


Gibt obere oder untere Grenze an

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Rückgabe:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


Gibt obere oder untere Grenze an

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |