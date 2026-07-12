---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Megadja a Sub-Superscript objektumot, amely egy alapból, valamint egy alsóindexből és felsőindexből áll, és az alap jobb oldalára van elhelyezve.
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

Meghatározza a Sub-Superscript objektumot, amely egy alapból és egy alsó- illetve felső indexből áll, és az alap jobb oldalára helyezkedik el.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt hoz létre a MathRightSubSuperscriptElement osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alsó index argumentum |
| [getSuperscript()](#getSuperscript--) | Felső index argumentum |
| [getAlignScripts()](#getAlignScripts--) | Meghatározza az alsó/felső indexek igazítását. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Meghatározza az alsó/felső indexek igazítását. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Új példányt hoz létre a MathRightSubSuperscriptElement osztályból.

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
> Example:
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
> Example:
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


Meghatározza az alsó/felső indexek igazítását. Ha igaz, az alsó és a felső index vízszintesen egymáshoz igazodik. Ha hamis, az alap alakjához lesznek igazítva. Alapértelmezett érték: hamis.

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


Meghatározza az alsó/felső indexek igazítását. Ha igaz, az alsó és a felső index vízszintesen egymáshoz igazodik. Ha hamis, az alap alakjához lesznek igazítva. Alapértelmezett érték: hamis.

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