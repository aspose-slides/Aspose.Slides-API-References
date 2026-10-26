---
title: IMathRadical
second_title: Aspose.Slides Java API referencia
description: Megadja a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll.
type: docs
url: /hu/com.aspose.slides/imathradical/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Megadja a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll. A gyök objektus példája: \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getDegree()](#getDegree--) | Fok argumentum |
| [getHideDegree()](#getHideDegree--) | Elrejti a fokot. Ha igaz, a fok nincs megjelenítve, ahogy a \\u221a\\ud835\\udc65 esetében |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Elrejti a fokot. Ha igaz, a fok nincs megjelenítve, ahogy a \\u221a\\ud835\\udc65 esetében |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement baseElem = radical.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Fok argumentum

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Elrejti a fokot. Ha igaz, a fok nincs megjelenítve, ahogy a \\u221a\\ud835\\udc65 esetében

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // kockagyök
>  radical.setHideDegree(true);
>  ```


**Visszatérési érték:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Elrejti a fokot. Ha igaz, a fok nincs megjelenítve, ahogy a \\u221a\\ud835\\udc65 esetében

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |