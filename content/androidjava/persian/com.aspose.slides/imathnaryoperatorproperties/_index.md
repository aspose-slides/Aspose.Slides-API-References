---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: ویژگی‌های IMathNaryOperator را مشخص می‌کند
type: docs
url: /fa/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

ویژگی‌های IMathNaryOperator را مشخص می‌کند
## متدها

| متد | توضیح |
| --- | --- |
| [getOperator()](#getOperator--) | کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقعیت محدودها (زیرنویس و بالانویس) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقعیت محدودها (زیرنویس و بالانویس) |
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

کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**باز می‌گرداند:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222b'

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

موقعیت محدودها (زیرنویس و بالانویس)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**باز می‌گرداند:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

موقعیت محدودها (زیرنویس و بالانویس)

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

**باز می‌گرداند:**
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

**باز می‌گرداند:**
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

**باز می‌گرداند:**
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