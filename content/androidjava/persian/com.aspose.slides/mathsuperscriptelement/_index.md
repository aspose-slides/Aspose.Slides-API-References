---
title: MathSuperscriptElement
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شیء بالانویس را مشخص می‌کند که از یک پایه و یک بالانویس با اندازهٔ کوچک‌تر که بالای آن و به سمت راست قرار دارد، تشکیل شده است
type: docs
url: /fa/com.aspose.slides/mathsuperscriptelement/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

شیء بالانویس را مشخص می‌کند که از یک پایه و یک بالانویس با اندازهٔ کوچک‌تر که بالای پایه و به سمت راست قرار دارد، تشکیل شده است

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathSuperscriptElement را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | بالانویس |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

یک نمونه جدید از کلاس MathSuperscriptElement را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

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
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
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