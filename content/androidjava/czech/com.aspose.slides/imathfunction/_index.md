---
title: IMathFunction
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Určuje funkci argumentu.
type: docs
url: /cs/com.aspose.slides/imathfunction/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Určuje funkci argumentu.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Název funkce Například názvy funkcí jsou sin a cos |
| [getBase()](#getBase--) | Argument funkce |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Název funkce Například názvy funkcí jsou sin a cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument funkce

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)