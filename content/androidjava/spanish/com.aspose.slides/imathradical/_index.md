---
title: IMathRadical
second_title: Aspose.Slides para Android a través de Java API Reference
description: Especifica la función radical que consta de una base y un grado opcional.
type: docs
url: /es/com.aspose.slides/imathradical/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Especifica la función radical, que consiste en una base y un grado opcional. Ejemplo de objeto radical es \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raíz cúbica
```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getDegree()](#getDegree--) | Argumento grado |
| [getHideDegree()](#getHideDegree--) | Ocultar grado Cuando es verdadero, el grado no se muestra, como en \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ocultar grado Cuando es verdadero, el grado no se muestra, como en \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raíz cúbica
>  IMathElement baseElem = radical.getBase();
>  ```


**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argumento grado

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raíz cúbica
>  IMathElement degreeElem = radical.getDegree();
> ```


**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Ocultar grado Cuando es verdadero, el grado no se muestra, como en \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raíz cúbica
>  radical.setHideDegree(true);
>  ```

**Devuelve:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Ocultar grado Cuando es verdadero, el grado no se muestra, como en \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raíz cúbica
>  radical.setHideDegree(true);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |