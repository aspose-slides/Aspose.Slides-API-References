---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides برای مرجع API جاوا
description: شی Sub-Superscript را مشخص می‌کند که شامل یک base و یک subscript و superscript است که در سمت راست base قرار می‌گیرند.
type: docs
url: /fa/com.aspose.slides/imathrightsubsuperscriptelement/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

شی Sub-Superscript را مشخص می‌کند که شامل یک base و یک subscript و superscript است که در سمت راست base قرار می‌گیرند.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان Base |
| [getSubscript()](#getSubscript--) | آرگومان Subscript |
| [getSuperscript()](#getSuperscript--) | آرگومان Superscript |
| [getAlignScripts()](#getAlignScripts--) | ترازبندی subscript/superscript را مشخص می‌کند. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ترازبندی subscript/superscript را مشخص می‌کند. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


آرگومان Base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


آرگومان Subscript

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
public abstract IMathElement getSuperscript()
```


آرگومان Superscript

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

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


ترازبندی subscript/superscript را مشخص می‌کند. وقتی مقدار true باشد، subscript و superscript به صورت افقی نسبت به یکدیگر هماهنگ می‌شوند. وقتی مقدار false باشد، به شکل base کرن می‌شوند. مقدار پیش‌فرض false است.

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

**بازگشت:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


ترازبندی subscript/superscript را مشخص می‌کند. وقتی مقدار true باشد، subscript و superscript به صورت افقی نسبت به یکدیگر هماهنگ می‌شوند. وقتی مقدار false باشد، به شکل base کرن می‌شوند. مقدار پیش‌فرض false است.

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