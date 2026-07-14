---
title: IMathSuperscriptElement
second_title: Aspose.Slides for Android عبر مرجع API لجافا
description: يحدد كائن الحرف المرتفع الذي يتكون من قاعدة وحرف مرتفع بحجم أصغر موضعًا أعلى وعلى اليمين
type: docs
url: /ar/com.aspose.slides/imathsuperscriptelement/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

يحدد كائن الحرف المرتفع، الذي يتكون من قاعدة وحرف مرتفع بحجم أصغر موضعًا أعلى وعلى اليمين

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الأساسي |
| [getSuperscript()](#getSuperscript--) | الرفع العلوي |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


الوسيط الأساسي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


الرفع العلوي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```


**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)