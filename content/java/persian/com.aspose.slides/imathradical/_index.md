---
title: IMathRadical
second_title: Aspose.Slides برای مرجع API جاوا
description: عملکرد رادیکال را که شامل پایه و به‌صورت اختیاری درجه است، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathradical/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

عملکرد رادیکال را مشخص می‌کند که شامل پایه و به‌صورت اختیاری درجه است. مثال شیٔ رادیکال عبارت است از \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشه‌ی مکعب
```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getDegree()](#getDegree--) | آرگومان درجه |
| [getHideDegree()](#getHideDegree--) | Hide degree اگر true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree اگر true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشهٔ مکعب
>  IMathElement baseElem = radical.getBase();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


آرگومان درجه

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشهٔ مکعب
>  IMathElement degreeElem = radical.getDegree();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree اگر true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشهٔ مکعب
>  radical.setHideDegree(true);
> ```

**باز می‌گرداند:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree اگر true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشهٔ مکعب
>  radical.setHideDegree(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |