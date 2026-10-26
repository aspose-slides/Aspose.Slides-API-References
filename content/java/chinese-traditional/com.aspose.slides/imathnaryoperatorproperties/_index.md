---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides 的 Java API 參考
description: 指定 IMathNaryOperator 的屬性
type: docs
url: /zh-hant/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

指定 IMathNaryOperator 的屬性
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOperator()](#getOperator--) | Nary 運算子字元，例如: '\\u2211'，'\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary 運算子字元，例如: '\\u2211'，'\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 限制的位置（下標和上標） |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 限制的位置（下標和上標） |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 運算子字元垂直增長以匹配其操作元高度 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 運算子字元垂直增長以匹配其操作元高度 |
| [getHideSubscript()](#getHideSubscript--) | 隱藏下標 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 隱藏下標 |
| [getHideSuperscript()](#getHideSuperscript--) | 隱藏上標 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 隱藏上標 |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary 運算子字元，例如: '\\u2211'，'\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**返回:**  
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary 運算子字元，例如: '\\u2211'，'\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


限制的位置（下標和上標）

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**返回:**  
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


限制的位置（下標和上標）

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


運算子字元垂直增長以匹配其操作元高度

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**返回:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


運算子字元垂直增長以匹配其操作元高度

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


隱藏下標

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**返回:**  
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


隱藏下標

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


隱藏上標

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**返回:**  
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


隱藏上標

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |