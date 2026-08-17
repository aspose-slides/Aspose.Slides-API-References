---
title: IMathRadical
second_title: Aspose.Slides für Java API Referenz
description: Gibt die Radikalfunktion an, die aus einer Basis und einem optionalen Grad besteht.
type: docs
url: /de/com.aspose.slides/imathradical/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Gibt die Radikalfunktion an, bestehend aus einer Basis und einem optionalen Grad. Beispiel für ein Radikalobjekt ist \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
```
## Methoden

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base Argument |
| [getDegree()](#getDegree--) | Degree Argument |
| [getHideDegree()](#getHideDegree--) | Hide degree Wenn true ist, wird der Grad nicht angezeigt, wie in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree Wenn true ist, wird der Grad nicht angezeigt, wie in \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base Argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  IMathElement baseElem = radical.getBase();
>  ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Degree Argument

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree Wenn true ist, wird der Grad nicht angezeigt, wie in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  radical.setHideDegree(true);
>  ```


**Rückgabewert:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree Wenn true ist, wird der Grad nicht angezeigt, wie in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // Kubikwurzel
>  radical.setHideDegree(true);
>  ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |