---
title: IMathLeftSubSuperscriptElement
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحدد كائن Sub-Superscript الذي يتكون من قاعدة وموضع فرعي وموضع عالٍ موضعين إلى يسار القاعدة.
type: docs
url: /ar/com.aspose.slides/imathleftsubsuperscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

يحدد كائن Sub-Superscript، الذي يتكون من قاعدة وموضع فرعي وموضع عالٍ موضعين إلى يسار القاعدة.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | وسيط القاعدة |
| [getSubscript()](#getSubscript--) | الموضع الفرعي |
| [getSuperscript()](#getSuperscript--) | الموضع العلوي |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


وسيط القاعدة

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


الموضع الفرعي

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

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


الموضع العلوي

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

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)