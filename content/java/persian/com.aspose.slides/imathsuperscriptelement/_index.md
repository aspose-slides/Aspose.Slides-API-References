---
title: IMathSuperscriptElement
second_title: Aspose.Slides برای Java - مرجع API
description: شیء بالانویس را مشخص می‌کند که شامل یک پایه و یک بالانویس با اندازه‌ی کوچک‌تر است که بالای سمت راست قرار می‌گیرد
type: docs
url: /fa/com.aspose.slides/imathsuperscriptelement/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

شیء بالانویس را مشخص می‌کند، که شامل یک پایه و یک بالانویس با اندازه‌ی کوچک‌تر است که بالای سمت راست قرار می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | پارامتر پایه |
| [getSuperscript()](#getSuperscript--) | بالانویس |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

پارامتر پایه

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**بازگشت:**
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

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)