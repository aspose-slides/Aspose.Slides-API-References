---
title: IMathSuperscriptElement
second_title: Aspose.Slides für Java API Referenz
description: Gibt das hochgestellte Objekt an, das aus einer Basis und einem verkleinerten Hochzeichen besteht, das darüber und rechts davon platziert ist
type: docs
url: /de/com.aspose.slides/imathsuperscriptelement/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Gibt das hochgestellte Objekt an, das aus einer Basis und einem verkleinerten Hochzeichen besteht, das darüber und rechts davon platziert ist

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSuperscript()](#getSuperscript--) | Hochzeichen |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Hochzeichen

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)