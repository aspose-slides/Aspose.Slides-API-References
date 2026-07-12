---
title: MathSubscriptElement
second_title: Aspose.Slides Android számára a Java API referenciáján keresztül
description: Megadja a subscript objektumot, amely egy alapból és egy kisebb méretű subscriptből áll, amely alulra és jobbra van elhelyezve.
type: docs
url: /hu/com.aspose.slides/mathsubscriptelement/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Meghatározza a subscript objektumot, amely egy alapból és egy kisebb méretű subscriptből áll, amely alulra és jobbra helyezkedik el.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt inicializál a MathSubscriptElement osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alsó index |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


Új példányt inicializál a MathSubscriptElement osztályból.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Alsó index

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]