---
title: IMathSuperscriptElement
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Spécifie l'objet exposant qui se compose d'une base et d'un exposant de taille réduite placé au-dessus et à droite
type: docs
url: /fr/com.aspose.slides/imathsuperscriptelement/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Spécifie l'objet exposant, qui se compose d'une base et d'un exposant de taille réduite placé au-dessus et à droite

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSuperscript()](#getSuperscript--) | Superscript |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()


Exposant

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement)