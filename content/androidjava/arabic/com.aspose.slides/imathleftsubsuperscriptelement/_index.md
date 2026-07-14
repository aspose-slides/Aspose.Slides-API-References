---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يحدد كائن Sub-Superscript الذي يتكون من قاعدة ورمز فرعي ورمز علوي موضوعة إلى يسار القاعدة.
type: docs
url: /ar/com.aspose.slides/imathleftsubsuperscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

يحدد كائن Sub-Superscript، الذي يتكون من قاعدة والرمز الفرعي والرمز العلوي موضوعة إلى يسار القاعدة.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | الرمز الفرعي |
| [getSuperscript()](#getSuperscript--) | الرمز العلوي |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل القاعدة

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


الرمز الفرعي

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


الرمز العلوي

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