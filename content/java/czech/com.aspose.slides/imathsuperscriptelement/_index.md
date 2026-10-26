---
title: IMathSuperscriptElement
second_title: Aspose.Slides pro Java referenční příručka API
description: Určuje objekt nadpisu, který se skládá ze základny a zmenšeného nadpisu umístěného nad a vpravo
type: docs
url: /cs/com.aspose.slides/imathsuperscriptelement/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Určuje objekt nadpisu, který se skládá ze základny a zmenšeného nadpisu umístěného nad a vpravo

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument základny |
| [getSuperscript()](#getSuperscript--) | Nadpis |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument základny

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


Nadpis

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