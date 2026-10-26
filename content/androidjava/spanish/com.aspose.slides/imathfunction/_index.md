---
title: IMathFunction
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Especifica una función de un argumento.
type: docs
url: /es/com.aspose.slides/imathfunction/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Especifica una función de un argumento.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Nombre de la función Por ejemplo, los nombres de funciones son sin y cos |
| [getBase()](#getBase--) | Argumento de la función |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Nombre de la función Por ejemplo, los nombres de funciones son sin y cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento de la función

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)