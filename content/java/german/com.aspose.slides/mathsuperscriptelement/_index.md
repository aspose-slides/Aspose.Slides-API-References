---
title: MathSuperscriptElement
second_title: Aspose.Slides für die Java-API-Referenz
description: Gibt das hochgestellte Objekt an, das aus einer Basis und einem verkleinerten hochgestellten Element besteht, das oberhalb und rechts davon positioniert ist.
type: docs
url: /de/com.aspose.slides/mathsuperscriptelement/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Gibt das hochgestellte Objekt an, das aus einer Basis und einem verkleinerten hochgestellten Element besteht, das oberhalb und rechts davon platziert ist.

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der Klasse MathSuperscriptElement. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Hochgestellt |
| [getChildren()](#getChildren--) | Kind-Elemente abrufen |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

Initialisiert eine neue Instanz der Klasse MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Hochgestellt

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Kind-Elemente abrufen

**Rückgabe:**
com.aspose.slides.IMathElement[]