---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides Java API Referansı
description: Alt ve üst simge nesnesini belirtir; bu nesne bir temel ve temelin sağına yerleştirilen bir alt simge ve bir üst simgeden oluşur.
type: docs
url: /tr/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Sub-Superscript nesnesini belirtir; bu nesne bir temel ve temel'in sağına yerleştirilen bir alt simge ve bir üst simgeden oluşur.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRightSubSuperscriptElement sınıfının yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSubscript()](#getSubscript--) | Alt simge bağımsız değişkeni |
| [getSuperscript()](#getSuperscript--) | Üst simge bağımsız değişkeni |
| [getAlignScripts()](#getAlignScripts--) | Alt simge/üst simge hizalamasını belirtir. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Alt simge/üst simge hizalamasını belirtir. |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |

### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

MathRightSubSuperscriptElement sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Alt simge bağımsız değişkeni

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

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Üst simge bağımsız değişkeni

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

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

Alt simge/üst simge hizalamasını belirtir. true olduğunda, alt simge ve üst simge birbirine yatay olarak hizalanır. false olduğunda, temel şekline göre kenar boşluğu ayarlanır. Varsayılan değer false'tur.

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

**Döndürür:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

Alt simge/üst simge hizalamasını belirtir. true olduğunda, alt simge ve üst simge birbirine yatay olarak hizalanır. false olduğunda, temel şekline göre kenar boşluğu ayarlanır. Varsayılan değer false'tur.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]