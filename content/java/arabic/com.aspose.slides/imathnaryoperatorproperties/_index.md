---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides ل-Java مرجع API
description: يحدد خصائص IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

يحدد خصائص IMathNaryOperator
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOperator()](#getOperator--) | حرف المشغل المتعدد على سبيل المثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | حرف المشغل المتعدد على سبيل المثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقع الحدود (الكتابة السفلية والكتابة العلوية) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقع الحدود (الكتابة السفلية والكتابة العلوية) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | حرف المشغل ينمو رأسياً ليتطابق مع ارتفاع المعامل |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | حرف المشغل ينمو رأسياً ليتطابق مع ارتفاع المعامل |
| [getHideSubscript()](#getHideSubscript--) | إخفاء النص السفلي |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | إخفاء النص السفلي |
| [getHideSuperscript()](#getHideSuperscript--) | إخفاء النص العلوي |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | إخفاء النص العلوي |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


حرف المشغل المتعدد على سبيل المثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**القيمة المرجعة:**  
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


حرف المشغل المتعدد على سبيل المثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


موقع الحدود (الكتابة السفلية والكتابة العلوية)

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**القيمة المرجعة:**  
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


موقع الحدود (الكتابة السفلية والكتابة العلوية)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


حرف المشغل ينمو رأسياً ليتطابق مع ارتفاع المعامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**القيمة المرجعة:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


حرف المشغل ينمو رأسياً ليتطابق مع ارتفاع المعامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


إخفاء النص السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**القيمة المرجعة:**  
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


إخفاء النص السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


إخفاء النص العلوي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**القيمة المرجعة:**  
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


إخفاء النص العلوي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |