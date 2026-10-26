---
title: IMathSubscriptElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء زیرنویس را مشخص می‌کند که از یک پایه و یک زیرنویس کوچکتر که در زیر و سمت راست قرار دارد، تشکیل شده است.
type: docs
url: /fa/com.aspose.slides/imathsubscriptelement/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

شیٔ زیرنویس را مشخص می‌کند که از پایه و یک زیرنویس کوچک‌سازی‌شده که در زیر و سمت راست قرار دارد، تشکیل شده است.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | نمایه |
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

**بازمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


نمایه

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**بازمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)