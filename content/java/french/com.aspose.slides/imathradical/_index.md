---
title: IMathRadical
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie la fonction radicande composée d'une base et d'un degré facultatif.
type: docs
url: /fr/com.aspose.slides/imathradical/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

Spécifie la fonction radicande, composée d’une base et d’un degré facultatif. Exemple d’objet radicande est \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // racine cubique
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de la base |
| [getDegree()](#getDegree--) | Argument du degré |
| [getHideDegree()](#getHideDegree--) | Hide degree lorsque la valeur est vraie, le degré n’est pas affiché, comme dans \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree lorsque la valeur est vraie, le degré n’est pas affiché, comme dans \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de la base

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // racine cubique
>  IMathElement baseElem = radical.getBase();
>  ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Argument du degré

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // racine cubique
>  IMathElement degreeElem = radical.getDegree();
>  ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree lorsque la valeur est vraie, le degré n’est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // racine cubique
>  radical.setHideDegree(true);
>  ```

**Renvoie:**  
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree lorsque la valeur est vraie, le degré n’est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // racine cubique
>  radical.setHideDegree(true);
>  ```


**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |