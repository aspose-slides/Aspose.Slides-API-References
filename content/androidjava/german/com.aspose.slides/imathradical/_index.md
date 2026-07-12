---
title: IMathRadical
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt die Radikalfunktion an, die aus einer Basis und einem optionalen Exponenten besteht.
type: docs
url: /de/com.aspose.slides/imathradical/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Gibt die Radikalfunktion an, die aus einer Basis und einem optionalen Exponenten besteht. Ein Beispiel für ein Radikalobjekt ist \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getDegree()](#getDegree--) | Exponentenargument |
| [getHideDegree()](#getHideDegree--) | Versteckt den Exponenten. Wenn true, wird der Exponent nicht angezeigt, wie bei \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Versteckt den Exponenten. Wenn true, wird der Exponent nicht angezeigt, wie bei \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  IMathElement baseElem = radical.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Exponentenargument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  IMathElement degreeElem = radical.getDegree();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Versteckt den Exponenten. Wenn true, wird der Exponent nicht angezeigt, wie bei \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  radical.setHideDegree(true);
> ```

**Rückgabewert:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Versteckt den Exponenten. Wenn true, wird der Exponent nicht angezeigt, wie bei \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  radical.setHideDegree(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |