---
title: IMathFunction
second_title: Aspose.Slides dla Androida poprzez Odwołanie API Java
description: Określa funkcję argumentu.
type: docs
url: /pl/com.aspose.slides/imathfunction/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Określa funkcję argumentu.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Nazwa funkcji Na przykład, nazwy funkcji to sin i cos |
| [getBase()](#getBase--) | Argument funkcji |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Nazwa funkcji Na przykład, nazwy funkcji to sin i cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument funkcji

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)