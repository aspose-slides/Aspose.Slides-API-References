---
title: IMathFraction
second_title: مرجع API Aspose.Slides برای Java
description: شیء کسر را که از صورت و مخرج تشکیل شده است و توسط نوار کسر از هم جدا می‌شود، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathfraction/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

این شیء کسر را تعریف می‌کند که شامل صورت و مخرج است که با یک نوار کسر از هم جدا شده‌اند. نوار کسر می‌تواند افقی یا قطری باشد، بسته به ویژگی‌های کسر. این شیء کسر همچنین برای نمایش تابع پشته استفاده می‌شود که یک عنصر را بالای عنصر دیگر قرار می‌دهد، بدون نوار کسر.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getFractionType()](#getFractionType--) | نوع کسر پیش‌فرض: Bar |
| [setFractionType(int value)](#setFractionType-int-) | نوع کسر پیش‌فرض: Bar |
| [getNumerator()](#getNumerator--) | صورت |
| [getDenominator()](#getDenominator--) | مخرج |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


نوع کسر پیش‌فرض: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**بازگشت:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


نوع کسر پیش‌فرض: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


صورت

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


مخرج

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)