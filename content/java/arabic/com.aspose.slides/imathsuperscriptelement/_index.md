---
title: IMathSuperscriptElement
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن الفوقية الذي يتكون من قاعدة ونص فائق بحجم أصغر موضوعًا فوق اليمين
type: docs
url: /ar/com.aspose.slides/imathsuperscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

يحدد كائن الفوقية، الذي يتكون من قاعدة ونص فائق بحجم أصغر موضوعًا فوق اليمين

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSuperscript()](#getSuperscript--) | النص الفائق |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**الإرجاع:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

النص الفائق

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**الإرجاع:**  
[IMathElement](../../com.aspose.slides/imathelement)