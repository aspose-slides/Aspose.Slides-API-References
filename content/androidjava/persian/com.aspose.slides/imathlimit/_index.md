---
title: IMathLimit
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء Limit را مشخص می‌کند که شامل متن بر روی baseline و متنی با اندازهٔ کوچک‌تر که مستقیماً بالای آن یا زیر آن قرار دارد.
type: docs
url: /fa/com.aspose.slides/imathlimit/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

شیء Limit را مشخص می‌کند که شامل متن روی baseline و متن با اندازهٔ کوچک‌تر که مستقیماً بالاتر یا پایین‌تر از آن قرار دارد.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getLimit()](#getLimit--) | آرگومان Limit |
| [getUpperLimit()](#getUpperLimit--) | محدودیت بالایی یا پایینی را مشخص می‌کند |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | محدودیت بالایی یا پایینی را مشخص می‌کند |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


آرگومان Limit

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


محدودیت بالایی یا پایینی را مشخص می‌کند

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**باز می‌گرداند:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


محدودیت بالایی یا پایینی را مشخص می‌کند

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |