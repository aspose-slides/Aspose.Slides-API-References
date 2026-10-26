---
title: IMathRadical
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica a função radical composta por uma base e um grau opcional.
type: docs
url: /pt/com.aspose.slides/imathradical/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Especifica a função radical, consistindo de uma base e um grau opcional. Exemplo de objeto radical é \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raiz cúbica
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getDegree()](#getDegree--) | Argumento de grau |
| [getHideDegree()](#getHideDegree--) | Ocultar grau Quando for verdadeiro, o grau não é mostrado, como em \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ocultar grau Quando for verdadeiro, o grau não é mostrado, como em \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raiz cúbica
>  IMathElement baseElem = radical.getBase();
>  ```


**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argumento de grau

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raiz cúbica
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Ocultar grau Quando for verdadeiro, o grau não é mostrado, como em \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raiz cúbica
>  radical.setHideDegree(true);
> ```

**Retorna:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Ocultar grau Quando for verdadeiro, o grau não é mostrado, como em \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // raiz cúbica
>  radical.setHideDegree(true);
>  ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |