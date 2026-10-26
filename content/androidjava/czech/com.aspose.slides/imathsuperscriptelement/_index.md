---
title: IMathSuperscriptElement
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje objekt horního indexu, který se skládá ze základního a zmenšeného horního indexu umístěného nad a vpravo
type: docs
url: /cs/com.aspose.slides/imathsuperscriptelement/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Určuje objekt horního indexu, který se skládá ze základního a zmenšeného horního indexu umístěného nad a vpravo

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getSuperscript()](#getSuperscript--) | Horní index |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Horní index

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)