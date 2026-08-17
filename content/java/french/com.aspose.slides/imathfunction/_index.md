---
title: IMathFunction
second_title: Référence de l'API Java Aspose.Slides
description: Spécifie une fonction d'un argument.
type: docs
url: /fr/com.aspose.slides/imathfunction/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Spécifie une fonction d'un argument.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
>  ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Nom de fonction Par exemple, les noms de fonction sont sin et cos |
| [getBase()](#getBase--) | Argument de fonction |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Nom de fonction Par exemple, les noms de fonction sont sin et cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```


**Retourne:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de fonction

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
>  ```

**Retourne:**
[IMathElement](../../com.aspose.slides/imathelement)