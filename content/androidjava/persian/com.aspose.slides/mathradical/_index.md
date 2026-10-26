---
title: MathRadical
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملکرد رادیکال را که شامل یک پایه و یک درجه اختیاری است مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathradical/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

توابع رادیکال را توصیف می‌کند که شامل یک پایه و یک درجه اختیاری است. مثال شی رادیکال \\u221a\\ud835\\udc65 است.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathRadical را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getDegree()](#getDegree--) | آرگومان درجه |
| [getHideDegree()](#getHideDegree--) | پنهان کردن درجه؛ وقتی true باشد، درجه نشان داده نمی‌شود، همان‌طور که در \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | پنهان کردن درجه؛ وقتی true باشد، درجه نشان داده نمی‌شود، همان‌طور که در \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


یک نمونه جدید از کلاس MathRadical را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | پایه |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | درجه |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


آرگومان درجه

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


پنهان کردن درجه؛ وقتی true باشد، درجه نشان داده نمی‌شود، همان‌طور که در \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**بازگشت:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


پنهان کردن درجه؛ وقتی true باشد، درجه نشان داده نمی‌شود، همان‌طور که در \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]