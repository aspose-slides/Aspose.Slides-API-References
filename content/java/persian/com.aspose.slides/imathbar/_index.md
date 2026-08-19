---
title: IMathBar
second_title: مرجع API Aspose.Slides برای جاوا
description: عملکرد نوار را مشخص می‌کند که شامل یک آرگومان پایه و یک نوار بالایی یا زیرانی است
type: docs
url: /fa/com.aspose.slides/imathbar/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

عملکرد نوار را مشخص می‌کند که شامل یک آرگومان پایه و یک نوار بالایی یا زیرانی است

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getPosition()](#getPosition--) | موقعیت خط نوار. |
| [setPosition(int value)](#setPosition-int-) | موقعیت خط نوار. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**باز می‌گرداند:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت خط نوار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**باز می‌گرداند:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت خط نوار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |   |