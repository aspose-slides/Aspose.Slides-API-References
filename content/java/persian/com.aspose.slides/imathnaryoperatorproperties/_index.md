---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides برای Java مرجع API
description: مشخصات ویژگی‌های IMathNaryOperator
type: docs
url: /fa/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

مشخصات ویژگی‌های IMathNaryOperator
## متدها

| متد | توضیح |
| --- | --- |
| [getOperator()](#getOperator--) | کاراکتر عملگر Nary، برای مثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | کاراکتر عملگر Nary، برای مثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقعیت محدودیت‌ها (زیرنویس و بالانویس) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقعیت محدودیت‌ها (زیرنویس و بالانویس) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد |
| [getHideSubscript()](#getHideSubscript--) | پنهان کردن زیرنویس |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | پنهان کردن زیرنویس |
| [getHideSuperscript()](#getHideSuperscript--) | پنهان کردن بالانویس |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | پنهان کردن بالانویس |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

کاراکتر عملگر Nary، برای مثال: '\\u2211', '\\u222b'

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
public abstract void setOperator(char value)
```

کاراکتر عملگر Nary، برای مثال: '\\u2211', '\\u222b'

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
public abstract int getLimitLocation()
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
public abstract void setLimitLocation(int value)
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
public abstract boolean getGrowToMatchOperandHeight()
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
public abstract void setGrowToMatchOperandHeight(boolean value)
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
public abstract boolean getHideSubscript()
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
public abstract void setHideSubscript(boolean value)
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
public abstract boolean getHideSuperscript()
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
public abstract void setHideSuperscript(boolean value)
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