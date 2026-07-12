---
title: MathSuperscriptElement
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir tabandan ve sağ üstte, daha küçük boyutta bir üst simge olarak yer alan bir üst simge nesnesini tanımlar
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

Taban ve sağ üstte, daha küçük boyutta yer alan bir üst simge içeren üst simge nesnesini tanımlar

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
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


MathSuperscriptElement sınıfının yeni bir örneğini başlatır.

--------------------

> ```
> Örnek:
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


Çocuk öğeleri al

**Döndürür:**  
com.aspose.slides.IMathElement[]