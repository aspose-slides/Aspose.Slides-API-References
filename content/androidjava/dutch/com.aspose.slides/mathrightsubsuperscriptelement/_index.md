---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het Sub-Superscript-object dat bestaat uit een basis en een subscript en superscript die rechts van de basis worden geplaatst.
type: docs
url: /nl/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die rechts van de basis worden geplaatst.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathRightSubSuperscriptElement-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript-argument |
| [getSuperscript()](#getSuperscript--) | Superscript-argument |
| [getAlignScripts()](#getAlignScripts--) | Specificeert de uitlijning van subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Specificeert de uitlijning van subscript/superscript. |
| [getChildren()](#getChildren--) | Haal kindelementen op |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Initialiseert een nieuw exemplaar van de MathRightSubSuperscriptElement-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
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

**Retour:**
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

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```


Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernt op de vorm van de basis. Standaardwaarde is false.

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

**Retour:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


Specificeert de uitlijning van subscript/superscript. Wanneer true, worden subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze gekernt op de vorm van de basis. Standaardwaarde is false.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal kindelementen op

**Retour:**
com.aspose.slides.IMathElement[]