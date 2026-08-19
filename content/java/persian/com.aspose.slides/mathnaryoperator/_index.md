---
title: MathNaryOperator
second_title: مرجع API Aspose.Slides برای Java
description: یک شیء ریاضی N-ary مانند جمع‌برداری و انتگرال را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathnaryoperator/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

یک شیء ریاضی N-ary را توصیف می‌کند، مانند جمع‌برداری و انتگرال. این شیء شامل یک عملگر، یک پایه (یا عملوند) و محدودیت‌های بالایی و پایینی اختیاری است. مثال‌هایی از عملگرهای N-ary عبارتند از: جمع‌برداری، اجتماع، اشتراک، انتگرال

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
| [getSubscript()](#getSubscript--) | آرگومان زیرنویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد پایین را تنظیم می‌کند. |
| [getSuperscript()](#getSuperscript--) | آرگومان بالانویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد بالا را تنظیم می‌کند. |
| [getOperator()](#getOperator--) | کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقعیت محدودیت‌ها (زیرنویس و بالانویس) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقعیت محدودیت‌ها (زیرنویس و بالانویس) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد |
| [getHideSubscript()](#getHideSubscript--) | پنهان‌سازی زیرنویس |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | پنهان‌سازی زیرنویس |
| [getHideSuperscript()](#getHideSuperscript--) | پنهان‌سازی بالانویس |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | پنهان‌سازی بالانویس |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
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
| operatorSymbol | char | نماد عملگر Nary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

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
| operatorSymbol | char | نماد عملگر Nary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |

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
| operatorSymbol | char | نماد عملگر Nary |
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

آرگومان زیرنویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد پایین را تنظیم می‌کند.

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

آرگومان بالانویس را مشخص می‌کند که به عنوان مثال در حالت انتگرال، حد بالا را تنظیم می‌کند.

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

کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222b'

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

کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222b'

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

موقعیت محدودیت‌ها (زیرنویس و بالانویس)

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

موقعیت محدودیت‌ها (زیرنویس و بالانویس)

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

کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد

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

کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد

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

پنهان‌سازی زیرنویس

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

پنهان‌سازی زیرنویس

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

پنهان‌سازی بالانویس

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

پنهان‌سازی بالانویس

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