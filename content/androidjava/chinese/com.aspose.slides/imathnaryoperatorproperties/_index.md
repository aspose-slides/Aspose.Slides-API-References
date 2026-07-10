---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 指定 IMathNaryOperator 的属性
type: docs
url: /zh/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

指定 IMathNaryOperator 的属性
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOperator()](#getOperator--) | Nary 操作符字符，例如：'\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary 操作符字符，例如：'\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 极限的位置（下标和上标） |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 极限的位置（下标和上标） |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 操作符字符垂直增长以匹配其操作数的高度 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 操作符字符垂直增长以匹配其操作数的高度 |
| [getHideSubscript()](#getHideSubscript--) | 隐藏下标 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 隐藏下标 |
| [getHideSuperscript()](#getHideSuperscript--) | 隐藏上标 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 隐藏上标 |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary 操作符字符，例如：'\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
>  ```
**Returns:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

Nary Operator Character For example: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

The location of limits (subscript and superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returns:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```
The location of limits (subscript and superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Operator Character grows vertically to match its operand height

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
>  ```

**Returns:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Operator Character grows vertically to match its operand height

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

Hide Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Returns:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

Hide Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

Hide Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Returns:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)


隐藏上标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |