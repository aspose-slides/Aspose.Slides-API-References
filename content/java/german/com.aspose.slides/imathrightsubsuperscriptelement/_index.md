---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides für Java API-Referenz
description: Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einer Tiefstellung und Hochstellung rechts von der Basis besteht.
type: docs
url: /de/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einer Tiefstellung und Hochstellung rechts von der Basis besteht.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Methoden

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Tiefstellenargument |
| [getSuperscript()](#getSuperscript--) | Hochstellenargument |
| [getAlignScripts()](#getAlignScripts--) | Legt die Ausrichtung von Subscript/Superscript fest. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Legt die Ausrichtung von Subscript/Superscript fest. |
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Tiefstellenargument

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

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Hochstellenargument

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

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Legt die Ausrichtung von Subscript/Superscript fest. Wenn *true*, werden Subscript und Superscript horizontal zueinander ausgerichtet. Wenn *false*, werden sie an die Form der Basis angepasst. Der Standardwert ist *false*.

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

**Rückgabe:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Legt die Ausrichtung von Subscript/Superscript fest. Wenn *true*, werden Subscript und Superscript horizontal zueinander ausgerichtet. Wenn *false*, werden sie an die Form der Basis angepasst. Der Standardwert ist *false*.

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

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |