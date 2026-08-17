---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: 指定 IMathNaryOperator 的属性
type: docs
url: /zh/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

指定 IMathNaryOperator 的属性
## 方法

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | 多元运算符字符，例如：'\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | 多元运算符字符，例如：'\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 极限的位置（下标和上标） |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 极限的位置（下标和上标） |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 运算符字符垂直增长以匹配其操作数高度 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 运算符字符垂直增长以匹配其操作数高度 |
| [getHideSubscript()](#getHideSubscript--) | 隐藏下标 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 隐藏下标 |
| [getHideSuperscript()](#getHideSuperscript--) | 隐藏上标 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 隐藏上标 |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

多元运算符字符，例如：'\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**返回值：**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

多元运算符字符，例如：'\\u2211', '\\u222b'

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

极限的位置（下标和上标）

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**返回值：**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

极限的位置（下标和上标）

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

运算符字符垂直增长以匹配其操作数高度

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**返回值：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

运算符字符垂直增长以匹配其操作数高度

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

隐藏下标

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**返回值：**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

隐藏下标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

隐藏上标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**返回值：**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

隐藏上标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |