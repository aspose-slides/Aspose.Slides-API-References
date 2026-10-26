---
title: IMathFraction
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء کسر را که شامل صورت و مخرج است و با یک خط کسر از هم جدا شده‌اند، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathfraction/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

شیء کسر را مشخص می‌کند که شامل صورت و مخرج است که با یک خط کسر از هم جدا شده‌اند. خط کسر می‌تواند افقی یا قطری باشد، بسته به ویژگی‌های کسر. شیء کسر همچنین برای نمایاندن تابع پشته استفاده می‌شود که یک عنصر را بالای عنصر دیگر قرار می‌دهد و خط کسری ندارد.

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
| [getFractionType()](#getFractionType--) | نوع Fraction پیش‌فرض: Bar |
| [setFractionType(int value)](#setFractionType-int-) | نوع Fraction پیش‌فرض: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


نوع Fraction پیش‌فرض: Bar

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


نوع Fraction پیش‌فرض: Bar

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


Numerator

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


Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)