---
title: MathSubscriptElement
second_title: Aspose.Slides für Java API-Referenz
description: Gibt das Tiefstellung-Objekt an, das aus einem Basisobjekt und einer verkleinerten Tiefstellung besteht, die unterhalb und rechts davon positioniert ist.
type: docs
url: /de/com.aspose.slides/mathsubscriptelement/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Gibt das Tiefstellung-Objekt an, das aus einem Basisobjekt und einer verkleinerten Tiefstellung besteht, die unterhalb und rechts davon positioniert ist.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathSubscriptElement-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubscript()](#getSubscript--) | Tiefstellung |
| [getChildren()](#getChildren--) | Kind-Elemente abrufen |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Initialisiert eine neue Instanz der MathSubscriptElement-Klasse.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```


**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Kind-Elemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[]