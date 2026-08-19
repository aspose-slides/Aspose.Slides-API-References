---
title: MathSubscriptElement
second_title: Aspose.Slides för Java API-referens
description: Anger nedsänkt-objektet som består av en bas och ett nedsänkt element i reducerad storlek placerat nedanför och till höger.
type: docs
url: /sv/com.aspose.slides/mathsubscriptelement/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Anger nedsänkt-objektet, som består av en bas och ett nedsänkt element i reducerad storlek placerat nedanför och till höger.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initierar en ny instans av MathSubscriptElement-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSubscript()](#getSubscript--) | Nedsänkt |
| [getChildren()](#getChildren--) | Hämta underordnade element |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

Initierar en ny instans av MathSubscriptElement-klassen.

--------------------

> ```
> Exempel:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Nedsänkt

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]