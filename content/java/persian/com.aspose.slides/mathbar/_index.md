---
title: MathBar
second_title: مرجع API Aspose.Slides برای جاوا
description: عملکرد نوار را مشخص می‌کند که شامل یک آرگومان پایه و یک نوار بالایی یا تحتانی است
type: docs
url: /fa/com.aspose.slides/mathbar/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

عملکرد نوار را مشخص می‌کند که شامل یک آرگومان پایه و یک نوار بالایی یا تحتانی است

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | MathBar را با نوار بالایی (موقعیت بالا) مقداردهی اولیه می‌کند |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | MathBar را با موقعیت مشخص مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getPosition()](#getPosition--) | موقعیت خط نوار. |
| [setPosition(int value)](#setPosition-int-) | موقعیت خط نوار. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


MathBar را با نوار بالایی (موقعیت بالا) مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که نوار به آن اعمال می‌شود |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


MathBar را با موقعیت مشخص مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که نوار به آن اعمال می‌شود |
| position | int | موقعیت خط نوار. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**بازگرداندن:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


موقعیت خط نوار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**بازگرداندن:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


موقعیت خط نوار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزند

**بازگرداندن:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


ویژگی‌های کاراکتر کنترل

**بازگرداندن:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps