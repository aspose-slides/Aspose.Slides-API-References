---
title: MathFraction
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء کسر را که از صورت و مخرج تشکیل شده و توسط یک خط کسر از هم جدا شده‌اند، توصیف می‌کند.
type: docs
url: /fa/com.aspose.slides/mathfraction/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

شیء کسر را که شامل صورت و مخرج است و با یک خط کسر جدا می‌شوند، توصیف می‌کند. خط کسر می‌تواند افقی یا قطری باشد، بسته به ویژگی‌های کسر. این شیء همچنین برای نمایش تابع انباشته استفاده می‌شود که یک عنصر را بالای عنصر دیگر قرار می‌دهد، بدون خط کسر.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | MathFraction را با صورت، مخرج و نوع مشخص شده مقداردهی اولیه می‌کند |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک MathFraction از نوع «Bar» را با صورت و مخرج مشخص شده مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getFractionType()](#getFractionType--) | نوع کسر پیش‌فرض: Bar |
| [setFractionType(int value)](#setFractionType-int-) | نوع کسر پیش‌فرض: Bar |
| [getNumerator()](#getNumerator--) | صورت |
| [getDenominator()](#getDenominator--) | مخرج |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

MathFraction را با صورت، مخرج و نوع مشخص شده مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |
| fractionType | int | نوع کسر |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```

یک MathFraction از نوع «Bar» را با صورت و مخرج مشخص شده مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**پارامترها:**  
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | صورت |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | مخرج |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
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
public final void setFractionType(int value)
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
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
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
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**بازگشت:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps