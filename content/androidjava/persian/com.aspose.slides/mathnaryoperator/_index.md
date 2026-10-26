---
title: MathNaryOperator
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء ریاضی N-آری مانند جمع و انتگرال را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathnaryoperator/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

یک شیء ریاضی N-آری را مشخص می‌کند، مانند جمع و انتگرال. این شامل یک عملگر، یک پایه (یا عملوند) و حدود بالایی و پایینی اختیاری است. مثال‌های عملگرهای N-آری عبارتند از: جمع، اجتماع، اشتراک، انتگرال

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getSubscript()](#getSubscript--) | آرگومان زیرنویس را مشخص می‌کند که به‌عنوان مثال، در مورد یک انتگرال، حد پایینی را تنظیم می‌کند |
| [getSuperscript()](#getSuperscript--) | آرگومان بالانویس را مشخص می‌کند که به‌عنوان مثال، در مورد یک انتگرال، حد بالایی را تنظیم می‌کند |
| [getOperator()](#getOperator--) | کاراکتر عملگر N-آری، به عنوان مثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | کاراکتر عملگر N-آری، به عنوان مثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | محل قرارگیری حدود (زیرنویس و بالانویس) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | محل قرارگیری حدود (زیرنویس و بالانویس) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | کاراکتر عملگر به‌صورت عمودی بزرگ می‌شود تا با ارتفاع عملوند هماهنگ شود |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | کاراکتر عملگر به‌صورت عمودی بزرگ می‌شود تا با ارتفاع عملوند هماهنگ شود |
| [getHideSubscript()](#getHideSubscript--) | پنهان کردن زیرنویس |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | پنهان کردن زیرنویس |
| [getHideSuperscript()](#getHideSuperscript--) | پنهان کردن بالانویس |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | پنهان کردن بالانویس |
| [getChildren()](#getChildren--) | دریافت عناصر فرزندی |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نماد عملگر N-آری |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایینی |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالایی |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نماد عملگر N-آری |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایینی |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نماد عملگر N-آری |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final IMathElement getSubscript()
```

آرگومان زیرنویس را مشخص می‌کند که به‌عنوان مثال، در مورد یک انتگرال، حد پایینی را تنظیم می‌کند

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
public final IMathElement getSuperscript()
```

آرگومان بالانویس را مشخص می‌کند که به‌عنوان مثال، در مورد یک انتگرال، حد بالایی را تنظیم می‌کند

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

کاراکتر عملگر N-آری، به عنوان مثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**بازگشت:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

کاراکتر عملگر N-آری، به عنوان مثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

محل قرارگیری حدود (زیرنویس و بالانویس)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**بازگشت:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

محل قرارگیری حدود (زیرنویس و بالانویس)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

کاراکتر عملگر به‌صورت عمودی بزرگ می‌شود تا با ارتفاع عملوند هماهنگ شود

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**بازگشت:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

کاراکتر عملگر به‌صورت عمودی بزرگ می‌شود تا با ارتفاع عملوند هماهنگ شود

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

پنهان کردن زیرنویس

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**بازگشت:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

پنهان کردن زیرنویس

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

پنهان کردن بالانویس

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**بازگشت:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

پنهان کردن بالانویس

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزندی

**بازگشت:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps