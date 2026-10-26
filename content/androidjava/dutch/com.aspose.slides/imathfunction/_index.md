---
title: IMathFunction
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een functie van een argument.
type: docs
url: /nl/com.aspose.slides/imathfunction/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Specificeert een functie van een argument.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
>  ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Functienaam Bijvoorbeeld, functienamen zijn sin en cos |
| [getBase()](#getBase--) | Functie-argument |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Functienaam Bijvoorbeeld, functienamen zijn sin en cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Functie-argument

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)