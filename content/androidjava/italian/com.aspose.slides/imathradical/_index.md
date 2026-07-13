---
title: IMathRadical
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica la funzione radicale composta da una base e da un grado opzionale.
type: docs
url: /it/com.aspose.slides/imathradical/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Specifica la funzione radicale, composta da una base e da un grado opzionale. Un esempio di oggetto radicale è \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // radice cubica
>  ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getDegree()](#getDegree--) | Argomento grado |
| [getHideDegree()](#getHideDegree--) | Nascondi grado Quando è true, il grado non è mostrato, come in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Nascondi grado Quando è true, il grado non è mostrato, come in \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argomento base

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // radice cubica
>  IMathElement baseElem = radical.getBase();
>  ```


**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argomento grado

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // radice cubica
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Nascondi grado Quando è true, il grado non è mostrato, come in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // radice cubica
>  radical.setHideDegree(true);
>  ```

**Restituisce:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Nascondi grado Quando è true, il grado non è mostrato, come in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // radice cubica
>  radical.setHideDegree(true);
>  ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |