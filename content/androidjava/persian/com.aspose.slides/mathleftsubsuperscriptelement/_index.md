---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شی Sub-Superscript را تعریف می‌کند که از یک پایه و زیرنویس و بالانویس تشکیل شده است و به سمت چپ پایه قرار می‌گیرد.
type: docs
url: /fa/com.aspose.slides/mathleftsubsuperscriptelement/
---
**وارثبری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
```
public final class MathLeftSubSuperscriptElement extends BaseScript implements IMathLeftSubSuperscriptElement
```

شی Sub-Superscript را توصیف می‌کند که شامل یک پایه و زیرنویس و بالانویس است که در سمت چپ پایه قرار گرفته‌اند.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathLeftSubSuperscriptElement را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSubscript()](#getSubscript--) | زیرنویس |
| [getSuperscript()](#getSuperscript--) | بالانویس |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


یک نمونه جدید از کلاس MathLeftSubSuperscriptElement را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
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

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
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

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]