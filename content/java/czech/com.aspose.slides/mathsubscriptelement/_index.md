---
title: MathSubscriptElement
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Určuje subskriptový objekt, který se skládá ze základny a zmenšeného subskriptu umístěného pod ní a vpravo.
type: docs
url: /cs/com.aspose.slides/mathsubscriptelement/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Určuje subskriptový objekt, který se skládá ze základny a zmenšeného subskriptu umístěného pod ní a vpravo.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathSubscriptElement. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subskript |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

Inicializuje novou instanci třídy MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Subskript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Vrácená hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získat podřízené prvky

**Vrácená hodnota:**
com.aspose.slides.IMathElement[]