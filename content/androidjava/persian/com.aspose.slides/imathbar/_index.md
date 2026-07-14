---
title: IMathBar
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملکرد بار را مشخص می‌کند که شامل یک آرگومان پایه و یک خط بالای‌بار یا زیربار است
type: docs
url: /fa/com.aspose.slides/imathbar/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

عملکرد بار را مشخص می‌کند که شامل یک آرگومان پایه و یک خط بالای‌بار یا زیربار است

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
| [getPosition()](#getPosition--) | موقعیت خط بار. |
| [setPosition(int value)](#setPosition-int-) | موقعیت خط بار. |
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

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


موقعیت خط بار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**بازگرداندن:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


موقعیت خط بار. پیش‌فرض: بالا

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |