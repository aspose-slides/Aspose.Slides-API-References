---
title: IMathLeftSubSuperscriptElement
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء زیر-بالا بنویس را توصیف می‌کند که از یک پایه و زیرنویس و بالانویس تشکیل شده است که در سمت چپ پایه قرار می‌گیرد.
type: docs
url: /fa/com.aspose.slides/imathleftsubsuperscriptelement/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

شیء زیر-بالا بنویس را توصیف می‌کند که از یک پایه و زیرنویس و بالانویس تشکیل شده است که در سمت چپ پایه قرار می‌گیرد.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | زیرنویس |
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
> ```

**بازگرداندن:**
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
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**بازگرداندن:**
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
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement)