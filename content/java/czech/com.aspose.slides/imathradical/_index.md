---
title: IMathRadical
second_title: Aspose.Slides pro Java - reference API
description: Specifikuje radikální funkci skládající se ze základu a volitelného stupně.
type: docs
url: /cs/com.aspose.slides/imathradical/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specifikuje radikální funkci, která se skládá ze základu a volitelného stupně. Příklad radikálního objektu je \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubický kořen
>  ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument základu |
| [getDegree()](#getDegree--) | Argument stupně |
| [getHideDegree()](#getHideDegree--) | Skrytí stupně. Když je true, stupeň se nezobrazuje, jako v \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Skrytí stupně. Když je true, stupeň se nezobrazuje, jako v \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument základu

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubický kořen
>  IMathElement baseElem = radical.getBase();
>  ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argument stupně

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubický kořen
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Skrytí stupně. Když je true, stupeň se nezobrazuje, jako v \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubický kořen
>  radical.setHideDegree(true);
>  ```


**Vrací:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Skrytí stupně. Když je true, stupeň se nezobrazuje, jako v \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kubický kořen
>  radical.setHideDegree(true);
>  ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |