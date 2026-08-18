---
title: IMathFunction
second_title: Aspose.Slides Java API referencia
description: Megad egy függvényt egy argumentumra.
type: docs
url: /hu/com.aspose.slides/imathfunction/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Megad egy függvényt egy argumentumra.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
>  ```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getName()](#getName--) | Függvény neve Például a függvénynevek a sin és a cos |
| [getBase()](#getBase--) | Függvény argumentum |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Függvény neve Például a függvénynevek a sin és a cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```


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