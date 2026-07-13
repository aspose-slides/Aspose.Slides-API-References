---
title: IMathFunction
second_title: Aspose.Slides för Android via Java API-referens
description: Anger en funktion av ett argument.
type: docs
url: /sv/com.aspose.slides/imathfunction/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Anger en funktion av ett argument.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Funktionsnamn Till exempel är funktionsnamnen sin och cos |
| [getBase()](#getBase--) | Funktionsargument |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Funktionsnamn Till exempel är funktionsnamnen sin och cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Funktionsargument

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)