---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides pour Java Référence API
description: Spécifie l'objet Sub-Superscript qui se compose d'une base et d'un indice et d'un exposant placés à droite de la base.
type: docs
url: /fr/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Spécifie l’objet Sub-Superscript, qui se compose d’une base et d’un indice et d’un exposant placés à droite de la base.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## Méthodes

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getSubscript()](#getSubscript--) | Argument d’indice |
| [getSuperscript()](#getSuperscript--) | Argument d’exposant |
| [getAlignScripts()](#getAlignScripts--) | Spécifie l’alignement du texte en indice/exposant. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Spécifie l’alignement du texte en indice/exposant. |
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Argument d’indice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Argument d’exposant

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Spécifie l’alignement du texte en indice/exposant. Lorsque la valeur est vraie, l’indice et l’exposant sont alignés horizontalement l’un par rapport à l’autre. Lorsque la valeur est fausse, ils sont ajustés à la forme de la base. La valeur par défaut est false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Renvoie :**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Spécifie l’alignement du texte en indice/exposant. Lorsque la valeur est vraie, l’indice et l’exposant sont alignés horizontalement l’un par rapport à l’autre. Lorsque la valeur est fausse, ils sont ajustés à la forme de la base. La valeur par défaut est false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |