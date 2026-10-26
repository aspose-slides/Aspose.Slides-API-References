---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides Java API referencia
description: Megadja a Sub-Superscript objektumot, amely egy bázisból és a bázis jobb oldalán elhelyezkedő alsó- és felső indexből áll.
type: docs
url: /hu/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Megadja az alsó- és felső index objektumot, amely egy bázisból és a bázis jobb oldalán elhelyezkedő alsó- és felső indexből áll.

--------------------

> ```
> Példa:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza a MathRightSubSuperscriptElement osztály új példányát. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alsó index argumentum |
| [getSuperscript()](#getSuperscript--) | Felső index argumentum |
| [getAlignScripts()](#getAlignScripts--) | Megadja az alsó/felső indexek igazítását. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Megadja az alsó/felső indexek igazítását. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

Létrehozza a MathRightSubSuperscriptElement osztály új példányát.

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

Alsó index argumentum

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Felső index argumentum

--------------------

> ```
> Példa:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

Megadja az alsó/felső indexek igazítását. Ha true, az alsó és felső indexek egymáshoz vízszintesen igazodnak. Ha false, a bázis alakjához kerülnek kerninggel. Alapértelmezett érték: false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Visszatérési érték:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

Megadja az alsó/felső indexek igazítását. Ha true, az alsó és felső indexek egymáshoz vízszintesen igazodnak. Ha false, a bázis alakjához kerülnek kerninggel. Alapértelmezett érték: false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]