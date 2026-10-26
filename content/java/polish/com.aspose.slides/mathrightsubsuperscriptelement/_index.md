---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides dla Java – dokumentacja API
description: Określa obiekt Sub-Superscript, który składa się z podstawy oraz podskryptu i superskryptu umieszczonych po prawej stronie podstawy.
type: docs
url: /pl/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Określa obiekt Sub-Superscript, który składa się z podstawy oraz podskryptu i superskryptu umieszczonych po prawej stronie podstawy.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathRightSubSuperscriptElement. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getSubscript()](#getSubscript--) | Argument podskryptu |
| [getSuperscript()](#getSuperscript--) | Argument superskryptu |
| [getAlignScripts()](#getAlignScripts--) | Określa wyrównanie podskryptu/superskriptu. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Określa wyrównanie podskryptu/superskriptu. |
| [getChildren()](#getChildren--) | Pobiera elementy potomne. |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

Inicjalizuje nową instancję klasy MathRightSubSuperscriptElement.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Argument podskryptu

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

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Argument superskryptu

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

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

Określa wyrównanie podskryptu/superskriptu. Gdy wartość jest true, podskrypt i superskrypt są wyrównane poziomo względem siebie. Gdy wartość jest false, są dopasowane do kształtu podstawy. Domyślna wartość to false.

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

**Zwraca:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

Określa wyrównanie podskryptu/superskriptu. Gdy wartość jest true, podskrypt i superskrypt są wyrównane poziomo względem siebie. Gdy wartość jest false, są dopasowane do kształtu podstawy. Domyślna wartość to false.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]