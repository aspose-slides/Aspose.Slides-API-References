---
title: IMathFunction
second_title: Aspose.Slides for Android a Java API hivatkozáson keresztül
description: Megad egy függvényt egy argumentumhoz.
type: docs
url: /hu/com.aspose.slides/imathfunction/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Megad egy függvényt egy argumentumhoz.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getName()](#getName--) | Függvény név Például a függvénynevek a sin és a cos |
| [getBase()](#getBase--) | Függvény argumentum |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Függvény név Például a függvénynevek a sin és a cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Függvény argumentum

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)