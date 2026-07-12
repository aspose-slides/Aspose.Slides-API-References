---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: IMathNaryOperator のプロパティを指定します
type: docs
url: /ja/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

IMathNaryOperator のプロパティを指定します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operator の文字 例: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator の文字 例: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 制限 の位置 (下付きと上付き) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 制限 の位置 (下付きと上付き) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 演算子文字がオペランドの高さに合わせて垂直に伸びる |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 演算子文字がオペランドの高さに合わせて垂直に伸びる |
| [getHideSubscript()](#getHideSubscript--) | 下付き文字を非表示 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 下付き文字を非表示 |
| [getHideSuperscript()](#getHideSuperscript--) | 上付き文字を非表示 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 上付き文字を非表示 |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary Operator の文字 例: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**戻り値:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary Operator の文字 例: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


制限 の位置 (下付きと上付き)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**戻り値:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


制限 の位置 (下付きと上付き)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


演算子文字がオペランドの高さに合わせて垂直に伸びる

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**戻り値:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


演算子文字がオペランドの高さに合わせて垂直に伸びる

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


下付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**戻り値:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


下付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


上付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**戻り値:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


上付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |