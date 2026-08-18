---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides for Java API Referansı
description: Temel bir nesne ve temelinin sağ tarafına yerleştirilen bir alt simge ve bir üst simgeden oluşan Alt-Ust simge nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Alt-üst nesnesini belirtir; bu nesne, bir temel ve temelinin sağ tarafına yerleştirilen bir alt simge ve üst simgeden oluşur.

--------------------

> ```
> Örnek:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getSubscript()](#getSubscript--) | Alt Simge argümanı |
| [getSuperscript()](#getSuperscript--) | Üst Simge argümanı |
| [getAlignScripts()](#getAlignScripts--) | Alt ve üst simgenin hizalamasını belirtir. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Alt ve üst simgenin hizalamasını belirtir. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Temel argüman

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Alt Simge argümanı

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Üst Simge argümanı

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

Alt ve üst simgenin hizalamasını belirtir. true olduğunda, alt ve üst simgeler birbirine yatay olarak hizalanır. false olduğunda, temelin şekline göre kenar boşlukları ayarlanır. Varsayılan değer false'tur.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
```

**Döndürür:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

Alt ve üst simgenin hizalamasını belirtir. true olduğunda, alt ve üst simgeler birbirine yatay olarak hizalanır. false olduğunda, temelin şekline göre kenar boşlukları ayarlanır. Varsayılan değer false'tur.

--------------------

> ```
> Örnek:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |