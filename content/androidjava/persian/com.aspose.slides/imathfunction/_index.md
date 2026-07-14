---
title: IMathFunction
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک تابع از یک آرگومان را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathfunction/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

یک تابع از یک آرگومان را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام تابع برای مثال، نام توابع sin و cos |
| [getBase()](#getBase--) | آرگومان تابع |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

نام تابع برای مثال، نام توابع sin و cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان تابع

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)