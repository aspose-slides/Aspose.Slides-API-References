---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides للـ Android عبر Java مرجع API
description: يحدد خصائص IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

يحدد خصائص IMathNaryOperator
## الطرق

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | حرف عامل Nary مثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | حرف عامل Nary مثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقع الحدود (المؤشر السفلي والعلوي) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقع الحدود (المؤشر السفلي والعلوي) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع operand |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع operand |
| [getHideSubscript()](#getHideSubscript--) | إخفاء المؤشر السفلي |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | إخفاء المؤشر السفلي |
| [getHideSuperscript()](#getHideSuperscript--) | إخفاء المؤشر العلوي |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | إخفاء المؤشر العلوي |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


حرف عامل Nary مثال: '\\u2211', '\\u222b'

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


حرف عامل Nary مثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


موقع الحدود (المؤشر السفلي والعلوي)

--------------------

> ```
> Example:
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


موقع الحدود (المؤشر السفلي والعلوي)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


حرف العامل ينمو عموديًا ليتطابق مع ارتفاع operand

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


حرف العامل ينمو عموديًا ليتطابق مع ارتفاع operand

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


إخفاء المؤشر السفلي

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


إخفاء المؤشر السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


إخفاء المؤشر العلوي

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


إخفاء المؤشر العلوي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |