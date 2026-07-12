---
title: MathSubscriptElement
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Gibt das Subscript-Objekt an, das aus einer Basis und einem verkleinerten Subscript unterhalb und rechts davon besteht.
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

Gibt das subscript-Objekt an, das aus einer Basis und einer verkleinerten subscript unterhalb und rechts davon platziert ist.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der MathSubscriptElement Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubscript()](#getSubscript--) | Tiefstellung |
| [getChildren()](#getChildren--) | Kinder-Elemente abrufen |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Initialisiert eine neue Instanz der MathSubscriptElement Klasse.

--------------------

> ```
> Beispiel:
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
> Beispiel:
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


Kinder-Elemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[]