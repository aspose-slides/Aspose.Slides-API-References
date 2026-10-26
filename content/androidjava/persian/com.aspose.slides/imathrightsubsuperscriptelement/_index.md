---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شی Sub-Superscript را تعریف می‌کند که شامل یک پایه و زیرنویس و بالانویس است که در سمت راست پایه قرار می‌گیرند.
type: docs
url: /fa/com.aspose.slides/imathrightsubsuperscriptelement/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

شی Sub-Superscript را تعریف می‌کند که شامل یک پایه و زیرنویس و بالانویس است که در سمت راست پایه قرار می‌گیرند.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
>  ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | آرگومان زیرنویس |
| [getSuperscript()](#getSuperscript--) | آرگومان بالانویس |
| [getAlignScripts()](#getAlignScripts--) | ترازبندی زیرنویس/بالانویس را مشخص می‌کند. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ترازبندی زیرنویس/بالانویس را مشخص می‌کند. |
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
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**باز می‌گردد:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
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

**باز می‌گردد:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

آرگومان بالانویس

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

**باز می‌گردد:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

ترازبندی زیرنویس/بالانویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر ترازبندی می‌شوند. وقتی مقدار false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

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

**باز می‌گردد:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

ترازبندی زیرنویس/بالانویس را مشخص می‌کند. وقتی مقدار true باشد، زیرنویس و بالانویس به صورت افقی نسبت به یکدیگر ترازبندی می‌شوند. وقتی مقدار false باشد، به شکل پایه کرن می‌شوند. مقدار پیش‌فرض false است.

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