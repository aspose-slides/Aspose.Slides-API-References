---
title: IMathRadical
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de radicaalfunctie bestaande uit een basis en een optionele graad.
type: docs
url: /nl/com.aspose.slides/imathradical/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specificeert de radicaalfunctie, bestaande uit een basis, en een optionele graad. Voorbeeld van radicaalobject is \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubuswortel
>  ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getDegree()](#getDegree--) | Degree argument |
| [getHideDegree()](#getHideDegree--) | Hide degree Wanneer true is, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree Wanneer true is, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubuswortel
>  IMathElement baseElem = radical.getBase();
>  ```


**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Degree argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubuswortel
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Retourneert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree Wanneer true is, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubuswortel
>  radical.setHideDegree(true);
>  ```

**Retourneert:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree Wanneer true is, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubuswortel
>  radical.setHideDegree(true);
>  ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |