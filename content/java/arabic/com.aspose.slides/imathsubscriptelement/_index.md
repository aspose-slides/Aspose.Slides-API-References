---
title: IMathSubscriptElement
second_title: Aspose.Slides للغة Java مرجع واجهة برمجة التطبيقات
description: يحدد كائن الحرف السفلي الذي يتكون من قاعدة وحرف سفلي مصغر موضع أسفل اليمين.
type: docs
url: /ar/com.aspose.slides/imathsubscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

يحدد كائن الحرف السفلي، الذي يتكون من قاعدة وحرف سفلي مصغر موضع أسفل اليمين.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | حرف سفلي |
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


**إرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


حرف سفلي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```


**إرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)