---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Megadja a Sub-Superscript objektumot, amely egy alapból és egy alsó- és felső indexből áll, amely az alap bal oldalára van helyezve.
type: docs
url: /hu/com.aspose.slides/mathleftsubsuperscriptelement/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
```
public final class MathLeftSubSuperscriptElement extends BaseScript implements IMathLeftSubSuperscriptElement
```

Megadja a Sub-Superscript objektumot, amely egy alapból és egy alsó- illetve felső indexből áll, amely az alap bal oldalára helyezkedik el.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt inicializál a MathLeftSubSuperscriptElement osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alsó index |
| [getSuperscript()](#getSuperscript--) | Felső index |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
### MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

Új példányt inicializál a MathLeftSubSuperscriptElement osztályból.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

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
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
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