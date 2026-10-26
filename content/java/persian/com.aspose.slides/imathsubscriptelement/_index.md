---
title: IMathSubscriptElement
second_title: Aspose.Slides برای Java - مرجع API
description: شیء زیرنویس را که شامل یک پایه و یک زیرنویس با اندازه کوچک‌تر است و در زیر و سمت راست قرار می‌گیرد، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathsubscriptelement/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

شیء زیرنویس را مشخص می‌کند که شامل یک پایه و یک زیرنویس با اندازهٔ کمتر است که در زیر و سمت راست قرار گرفته‌اند.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
>  ```

## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | زیرنویس |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

زیرنویس

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)