---
title: MathRightSubSuperscriptElement
second_title: مرجع API Aspose.Slides برای جاوا
description: شی Sub-Superscript را مشخص می‌کند که شامل یک پایه و زیرنویس و بالانویس است که در سمت راست پایه قرار می‌گیرند.
type: docs
url: /fa/com.aspose.slides/mathrightsubsuperscriptelement/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

شی Sub-Superscript را مشخص می‌کند که شامل یک پایه و زیرنویس و بالانویس است که در سمت راست پایه قرار می‌گیرند.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathRightSubSuperscriptElement را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSubscript()](#getSubscript--) | آرگومان زیرنویس |
| [getSuperscript()](#getSuperscript--) | آرگومان بالانویس |
| [getAlignScripts()](#getAlignScripts--) | تطبیق موقعیت زیرنویس/بالانویس را مشخص می‌کند. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | تطبیق موقعیت زیرنویس/بالانویس را مشخص می‌کند. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزندی |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

یک نمونه جدید از کلاس MathRightSubSuperscriptElement را مقداردهی اولیه می‌کند.

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

آرگومان زیرنویس

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

آرگومان بالانویس

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

تطبیق موقعیت زیرنویس/بالانویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌سطر می‌شوند. وقتی مقدار false باشد، نسبت به شکل پایه تنظیم (kerning) می‌شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**بازگشت:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

تطبیق موقعیت زیرنویس/بالانویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر هم‌سطر می‌شوند. وقتی مقدار false باشد، نسبت به شکل پایه تنظیم (kerning) می‌شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> مثال:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزندی

**بازگشت:**
com.aspose.slides.IMathElement[]