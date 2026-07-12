---
title: IMathRadical
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Bir taban ve isteğe bağlı bir derece içeren radikal fonksiyonu belirtir.
type: docs
url: /tr/com.aspose.slides/imathradical/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Radikal fonksiyonu belirler; bir taban ve isteğe bağlı bir derece içerir. Radikal nesne örneği \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
```
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Taban argümanı |
| [getDegree()](#getDegree--) | Derece argümanı |
| [getHideDegree()](#getHideDegree--) | Gizli derece: true olduğunda derece gösterilmez, gibi \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Gizli derece: true olduğunda derece gösterilmez, gibi \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Taban argümanı

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  IMathElement baseElem = radical.getBase();
```

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
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  IMathElement degreeElem = radical.getDegree();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Gizli derece: true olduğunda derece gösterilmez, gibi \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  radical.setHideDegree(true);
> ```

**Döndürür:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Gizli derece: true olduğunda derece gösterilmez, gibi \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // küp kökü
>  radical.setHideDegree(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |