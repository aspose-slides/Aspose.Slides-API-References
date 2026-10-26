---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء زیرنوشت-بالانویس را که شامل یک پایه و یک زیرنویس و بالانویس قرار گرفته در سمت راست پایه است، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathrightsubsuperscriptelement/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

شیء زیرنوشت-بالانویس را مشخص می‌کند که شامل یک پایه و یک زیرنویس و بالانویس است که در سمت راست پایه قرار می‌گیرند.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathRightSubSuperscriptElement را مقداردهی اولیه می‌کند. |

## متدها

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | آرگومان زیرنویس |
| [getSuperscript()](#getSuperscript--) | آرگومان فوق‌نویس |
| [getAlignScripts()](#getAlignScripts--) | ترازبندی زیرنویس/فوق‌نویس را مشخص می‌کند. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ترازبندی زیرنویس/فوق‌نویس را مشخص می‌کند. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |

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

**مقدار بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

آرگومان فوق‌نویس

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**مقدار بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

ترازبندی زیرنویس/فوق‌نویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و فوق‌نویس به صورت افقی نسبت به یکدیگر هم‌تراز می‌شوند. وقتی مقدار false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**مقدار بازگشت:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

ترازبندی زیرنویس/فوق‌نویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و فوق‌نویس به صورت افقی نسبت به یکدیگر هم‌تراز می‌شوند. وقتی مقدار false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> Example:
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

دریافت عناصر فرزند

**مقدار بازگشت:**
com.aspose.slides.IMathElement[]