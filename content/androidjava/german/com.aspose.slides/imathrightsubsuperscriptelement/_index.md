---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt das Sub-Superscript-Objekt an, das aus einer Basis und einem tief- bzw. hochgestellten Zeichen besteht, das rechts von der Basis platziert wird.
type: docs
url: /de/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Gibt das Sub-Superscript-Objekt an, das aus einer Basis und einem tief- bzw. hochgestellten Zeichen besteht, das rechts von der Basis platziert wird.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Tiefgestelltes Argument |
| [getSuperscript()](#getSuperscript--) | Hochgestelltes Argument |
| [getAlignScripts()](#getAlignScripts--) | Gibt die Ausrichtung von Subscript/Superscript an. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Gibt die Ausrichtung von Subscript/Superscript an. |
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
```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Tiefgestelltes Argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Hochgestelltes Argument

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


**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Gibt die Ausrichtung von Subscript/Superscript an. Wenn *true*, sind Subscript und Superscript horizontal zueinander ausgerichtet. Wenn *false*, werden sie an die Form der Basis angepasst. Der Standardwert ist *false*.

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

**Rückgabewert:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Gibt die Ausrichtung von Subscript/Superscript an. Wenn *true*, sind Subscript und Superscript horizontal zueinander ausgerichtet. Wenn *false*, werden sie an die Form der Basis angepasst. Der Standardwert ist *false*.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |