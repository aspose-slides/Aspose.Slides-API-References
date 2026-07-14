---
title: IMathSubscriptElement
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يحدد كائن الفهرس الذي يتكون من قاعدة ومؤشر أصغر حجماً موضعاً أسفل اليمين.
type: docs
url: /ar/com.aspose.slides/imathsubscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

يحدد كائن الفهرس، الذي يتكون من قاعدة ومؤشر أصغر حجماً موضعاً أسفل اليمين.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## الدوال

| الدالة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | المؤشر |
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


المؤشر

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)