---
title: IMathNaryOperator
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک شیء ریاضی N-آری مانند جمع و انتگرال را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathnaryoperator/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

یک شی ریاضی N-آری را مشخص می‌کند، مانند جمع و انتگرال. این شامل یک عملگر، یک پایه (یا عملوند) و حدود بالایی و پایینی اختیاری است. مثال‌های عملگرهای N-آری عبارتند از: جمع، اجتماع، اشتراک، انتگرال

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | یک آرگومان زیرنویس را مشخص می‌کند که، به عنوان مثال، در مورد یک انتگرال، حد پایین را تنظیم می‌کند |
| [getSuperscript()](#getSuperscript--) | یک آرگومان فوق‌نویس را مشخص می‌کند که، به عنوان مثال، در مورد یک انتگرال، حد بالا را تنظیم می‌کند |
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
```

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


یک آرگومان زیرنویس را مشخص می‌کند که، به عنوان مثال، در مورد یک انتگرال، حد پایین را تنظیم می‌کند

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


یک آرگومان فوق‌نویس را مشخص می‌کند که، به عنوان مثال، در مورد یک انتگرال، حد بالا را تنظیم می‌کند

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**بازگرداندن:**
[IMathElement](../../com.aspose.slides/imathelement)