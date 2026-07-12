---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einer Tief- und Hochstellung besteht, die links von der Basis platziert ist.
type: docs
url: /de/com.aspose.slides/mathleftsubsuperscriptelement/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
```
public final class MathLeftSubSuperscriptElement extends BaseScript implements IMathLeftSubSuperscriptElement
```

Gibt das Sub-Superscript-Objekt an, das aus einer Basis sowie einer Tief- und Hochstellung besteht, die links von der Basis positioniert sind.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der Klasse MathLeftSubSuperscriptElement. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubscript()](#getSubscript--) | Tiefstellung |
| [getSuperscript()](#getSuperscript--) | Hochstellung |
| [getChildren()](#getChildren--) | Kinder-Elemente abrufen |
### MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Initialisiert eine neue Instanz der Klasse MathLeftSubSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```


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


Tiefstellung

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```


**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Hochstellung

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSuperscript.getSuperscript();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Kinder-Elemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[]