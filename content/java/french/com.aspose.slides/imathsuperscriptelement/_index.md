---
title: IMathSuperscriptElement
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l’objet exposant qui se compose d’une base et d’un exposant de taille réduite placé au-dessus et à droite
type: docs
url: /fr/com.aspose.slides/imathsuperscriptelement/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Spécifie l’objet exposant, qui se compose d’une base et d’un exposant de taille réduite placé au-dessus et à droite

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getSuperscript()](#getSuperscript--) | Exposant |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```


**Retourne :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


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

**Retourne :**
[IMathElement](../../com.aspose.slides/imathelement)