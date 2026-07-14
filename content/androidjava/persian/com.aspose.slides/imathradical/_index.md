---
title: IMathRadical
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملکرد رادیکال را که شامل پایه و یک درجه اختیاری است، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathradical/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

عملکرد رادیکال را تعیین می‌کند که شامل پایه و یک درجه اختیاری است. مثال شی رادیکال \\u221a\\ud835\\udc65 می‌باشد.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشه مکعب
```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getDegree()](#getDegree--) | آرگومان درجه |
| [getHideDegree()](#getHideDegree--) | Hide degree وقتی true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree وقتی true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشه مکعب
>  IMathElement baseElem = radical.getBase();
>  ```

**بازمی‌گرداند:**
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
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشه مکعب
>  IMathElement degreeElem = radical.getDegree();
>  ```

**بازمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Hide degree وقتی true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // ریشه مکعب
>  radical.setHideDegree(true);
>  ```


**بازمی‌گرداند:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Hide degree وقتی true باشد، درجه نشان داده نمی‌شود، همانند \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |