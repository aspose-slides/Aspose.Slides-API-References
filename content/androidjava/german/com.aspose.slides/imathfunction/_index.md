---
title: IMathFunction
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt eine Funktion eines Arguments an.
type: docs
url: /de/com.aspose.slides/imathfunction/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Gibt eine Funktion eines Arguments an.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Funktionsname Zum Beispiel sind Funktionsnamen sin und cos |
| [getBase()](#getBase--) | Funktionsargument |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Funktionsname Zum Beispiel sind Funktionsnamen sin und cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Rückgabewert:**
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

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)