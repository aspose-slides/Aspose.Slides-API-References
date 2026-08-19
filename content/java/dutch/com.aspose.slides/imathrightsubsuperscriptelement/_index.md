---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert het Sub-Superscript-object dat bestaat uit een basis en een subscript en superscript die rechts van de basis worden geplaatst.
type: docs
url: /nl/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die rechts van de basis worden geplaatst.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getSubscript()](#getSubscript--) | Subscriptargument |
| [getSuperscript()](#getSuperscript--) | Superscriptargument |
| [getAlignScripts()](#getAlignScripts--) | Specificeert de uitlijning van subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Specificeert de uitlijning van subscript/superscript. |
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

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Subscriptargument

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
public abstract IMathElement getSuperscript()
```

Superscriptargument

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
public abstract boolean getAlignScripts()
```

Specificeert de uitlijning van subscript/superscript. Wanneer true, zijn subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze aangepast aan de vorm van de basis. Standaardwaarde is false.

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
public abstract void setAlignScripts(boolean value)
```

Specificeert de uitlijning van subscript/superscript. Wanneer true, zijn subscript en superscript horizontaal op elkaar uitgelijnd. Wanneer false, worden ze aangepast aan de vorm van de basis. Standaardwaarde is false.

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