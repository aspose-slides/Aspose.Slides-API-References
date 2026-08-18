---
title: MathSuperscriptElement
second_title: Aspose.Slides for Java API Referansı
description: Üst simge nesnesini belirtir; bu nesne, bir temel ve sağ üstte ve sağda konumlandırılmış küçültülmüş bir üst simge içerir.
type: docs
url: /tr/com.aspose.slides/mathsuperscriptelement/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

Üst simge nesnesini belirtir; bu nesne, sağ üstte ve sağda konumlandırılmış bir temel ve küçültülmüş bir üst simge içerir

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSuperscriptElement sınıfının yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | Üst Simge |
| [getChildren()](#getChildren--) | Alt öğeleri al |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


MathSuperscriptElement sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Üst Simge

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]