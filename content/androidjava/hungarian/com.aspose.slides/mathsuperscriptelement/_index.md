---
title: MathSuperscriptElement
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Megadja a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el
type: docs
url: /hu/com.aspose.slides/mathsuperscriptelement/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Meghatározza a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el.

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt inicializál a MathSuperscriptElement osztályban. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Felső index |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


Új példányt inicializál a MathSuperscriptElement osztályban.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Felső index

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermek elemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]