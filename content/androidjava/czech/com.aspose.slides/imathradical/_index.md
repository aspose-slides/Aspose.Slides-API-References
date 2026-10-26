---
title: IMathRadical
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Specifikuje radikální funkci, která se skládá ze základu a volitelného exponentu.
type: docs
url: /cs/com.aspose.slides/imathradical/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specifikuje radikální funkci, skládající se ze základu a volitelného exponentu. Příkladem radikálního objektu je \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubická odmocnina
>  ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getDegree()](#getDegree--) | Degree argument |
| [getHideDegree()](#getHideDegree--) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument základu

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubická odmocnina
>  IMathElement baseElem = radical.getBase();
>  ```


**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argument exponentu

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubická odmocnina
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Skryje exponent. Když je true, exponent není zobrazen, jako v \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubická odmocnina
>  radical.setHideDegree(true);
>  ```

**Vrací:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Skryje exponent. Když je true, exponent není zobrazen, jako v \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubická odmocnina
>  radical.setHideDegree(true);
>  ```


**Parametry:**
| Parametr | Type | Popis |
| --- | --- | --- |
| value | boolean |  |