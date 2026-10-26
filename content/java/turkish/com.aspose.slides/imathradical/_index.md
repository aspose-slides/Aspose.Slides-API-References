---
title: IMathRadical
second_title: Aspose.Slides için Java API Referansı
description: Bir temel ve isteğe bağlı bir derece içeren radikal fonksiyonu belirtir.
type: docs
url: /tr/com.aspose.slides/imathradical/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Radikal fonksiyonu belirtir; bir temel ve isteğe bağlı bir derece içerir. Radikal nesne örneği \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getDegree()](#getDegree--) | Derece argümanı |
| [getHideDegree()](#getHideDegree--) | Derece gizlenir; true olduğunda, derece gösterilmez, örnek \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Derece gizlenir; true olduğunda, derece gösterilmez, örnek \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  IMathElement baseElem = radical.getBase();
>  ```


**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

Derece argümanı

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement degreeElem = radical.getDegree();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Derece gizlenir; true olduğunda, derece gösterilmez, örnek \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Döndürür:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Derece gizlenir; true olduğunda, derece gösterilmez, örnek \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  radical.setHideDegree(true);
>  ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |