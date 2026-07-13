---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Specifica l'oggetto Sub-Superscript che è composto da una base e da un pedice e un apice posizionati a destra della base.
type: docs
url: /it/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Specifica l'oggetto Sub-Superscript, che è composto da una base e da un pedice e un apice posizionati a destra della base.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathRightSubSuperscriptElement. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSubscript()](#getSubscript--) | Argomento del pedice |
| [getSuperscript()](#getSuperscript--) | Argomento dell'apice |
| [getAlignScripts()](#getAlignScripts--) | Specifica l'allineamento del pedice/apice. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Specifica l'allineamento del pedice/apice. |
| [getChildren()](#getChildren--) | Recupera gli elementi figli |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Inizializza una nuova istanza della classe MathRightSubSuperscriptElement.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Argomento del pedice

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


**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Argomento dell'apice

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

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```


Specifica l'allineamento del pedice/apice. Quando true, il pedice e l'apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.

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


**Restituisce:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


Specifica l'allineamento del pedice/apice. Quando true, il pedice e l'apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Recupera gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]