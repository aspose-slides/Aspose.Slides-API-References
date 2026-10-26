---
title: IMathSuperscriptElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء بالانویس را مشخص می‌کند که از یک پایه و یک بالانویس کوچک‌نمایی تشکیل شده است که بالای و سمت راست آن قرار دارد
type: docs
url: /fa/com.aspose.slides/imathsuperscriptelement/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

شیء بالانویس را مشخص می‌کند که از یک پایه و یک بالانویس کوچک‌نمایی تشکیل شده است که بالای و سمت راست آن قرار دارد

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## متدها

| متد | توضیحات |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSuperscript()](#getSuperscript--) | بالانویس |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**بازمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

بالانویس

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**بازمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)