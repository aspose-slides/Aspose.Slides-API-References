---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides för Java API-referens
description: Specificerar Sub-Superscript-objektet som består av en bas samt ett subscript och superscript placerade till höger om basen.
type: docs
url: /sv/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Specificerar Sub-Superscript-objektet, som består av en bas och ett subscript samt superscript placerade till höger om basen.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Skapar en ny instans av klassen MathRightSubSuperscriptElement. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript-argument |
| [getSuperscript()](#getSuperscript--) | Superscript-argument |
| [getAlignScripts()](#getAlignScripts--) | Anger justeringen av subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Anger justeringen av subscript/superscript. |
| [getChildren()](#getChildren--) | Hämtar barn-element |

### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Skapar en ny instans av klassen MathRightSubSuperscriptElement.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Subscript-argument

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

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Superscript-argument

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

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```


Anger justeringen av subscript/superscript. När true är subscript och superscript horisontellt justerade mot varandra. När false kerna de till basens form. Standardvärde är false.

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

**Returnerar:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


Anger justeringen av subscript/superscript. När true är subscript och superscript horisontellt justerade mot varandra. När false kerna de till basens form. Standardvärde är false.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Hämtar barn-element

**Returnerar:**
com.aspose.slides.IMathElement[]