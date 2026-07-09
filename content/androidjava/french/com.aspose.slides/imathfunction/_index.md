---
title: IMathFunction
second_title: Aspose.Slides pour Android via la référence API Java
description: Spécifie une fonction d'un argument.
type: docs
url: /fr/com.aspose.slides/imathfunction/
---
**Toutes les interfaces implémentées :**  
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
> ```
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Function name For example, function names are sin and cos |
| [getBase()](#getBase--) | Function Argument |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Function name For example, function names are sin and cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()


Argument de fonction

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Renvoie :**  
[IMathElement](../../com.aspose.slides/imathelement)