---
title: IMathSuperscriptElement
second_title: Android için Aspose.Slides Java API Referansı
description: Üst simge nesnesini belirtir; bu nesne bir temel ve sağa ve yukarıya konumlandırılmış, daha küçük boyutta bir üst simge içerir.
type: docs
url: /tr/com.aspose.slides/imathsuperscriptelement/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Superscript nesnesini belirtir; bu nesne, tabanın üstüne ve sağına konumlandırılmış, daha küçük boyutta bir üst simge içerir.

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getSuperscript()](#getSuperscript--) | Üst simge |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Üst simge

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)