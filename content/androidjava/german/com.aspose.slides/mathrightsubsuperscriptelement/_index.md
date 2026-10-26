---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides für Android über Java API Referenz
description: Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einem tiefgestellten und einem hochgestellten Element besteht, das rechts von der Basis positioniert ist.
type: docs
url: /de/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einem tiefgestellten und einem hochgestellten Element besteht, das rechts von der Basis positioniert ist.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der Klasse MathRightSubSuperscriptElement. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript-Argument |
| [getSuperscript()](#getSuperscript--) | Superscript-Argument |
| [getAlignScripts()](#getAlignScripts--) | Gibt die Ausrichtung von Subscript/Superscript an. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Gibt die Ausrichtung von Subscript/Superscript an. |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Initialisiert eine neue Instanz der Klasse MathRightSubSuperscriptElement.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Subscript-Argument

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
public final IMathElement getSuperscript()
```


Superscript-Argument

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
public final boolean getAlignScripts()
```


Gibt die Ausrichtung von Subscript/Superscript an. Wenn true, sind Subscript und Superscript horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Der Standardwert ist false.

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
public final void setAlignScripts(boolean value)
```


Gibt die Ausrichtung von Subscript/Superscript an. Wenn true, sind Subscript und Superscript horizontal zueinander ausgerichtet. Wenn false, werden sie an die Form der Basis angepasst. Der Standardwert ist false.

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gibt Kindelemente zurück

**Rückgabe:**
com.aspose.slides.IMathElement[]