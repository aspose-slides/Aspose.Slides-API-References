---
title: MathSubscriptElement
second_title: Aspose.Slides voor Java API Referentie
description: Specificeert het subscriptobject dat bestaat uit een basis en een verkleind subscript dat onder en rechts geplaatst wordt.
type: docs
url: /nl/com.aspose.slides/mathsubscriptelement/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Specificeert het subscriptobject, dat bestaat uit een basis en een verkleind subscript dat onder en rechts geplaatst wordt.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathSubscriptElement-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript |
| [getChildren()](#getChildren--) | Haalt kindelementen op |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Initialiseert een nieuw exemplaar van de MathSubscriptElement-klasse.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Subscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haalt kindelementen op

**Retour:**
com.aspose.slides.IMathElement[]