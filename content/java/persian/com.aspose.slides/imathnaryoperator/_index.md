---
title: IMathNaryOperator
second_title: Aspose.Slides برای مرجع API جاوا
description: یک شیء ریاضی N-ary را مشخص می‌کند، مانند Summation و Integral.
type: docs
url: /fa/com.aspose.slides/imathnaryoperator/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

یک شیء ریاضی N-ار را مشخص می‌کند، مانند Summation و Integral. این شامل یک عملگر، یک پایه (یا عملوند) و حدود بالایی و پایینی اختیاری است. مثال‌های عملگرهای N-ار شامل: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | یک آرگومان زیرنویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد پایینی را تنظیم می‌کند |
| [getSuperscript()](#getSuperscript--) | یک آرگومان بالانویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد بالایی را تنظیم می‌کند |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

یک آرگومان زیرنویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد پایینی را تنظیم می‌کند

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

یک آرگومان بالانویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد بالایی را تنظیم می‌کند

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)