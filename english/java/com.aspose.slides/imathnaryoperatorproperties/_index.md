---
title: IMathNaryOperatorProperties
second_title: Aspose.Sildes for Java API Reference
description: p
 Specifies properties of IMathNaryOperator
type: docs
weight: 907
url: /java/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Specifies properties of IMathNaryOperator
## Methods

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operator Character For example: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator Character For example: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | The location of limits (subscript and superscript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | The location of limits (subscript and superscript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator Character grows vertically to match its operand height |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator Character grows vertically to match its operand height |
| [getHideSubscript()](#getHideSubscript--) | Hide Subscript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Hide Subscript |
| [getHideSuperscript()](#getHideSuperscript--) | Hide Superscript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Hide Superscript |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary Operator Character For example: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

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
> ```

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
> ```

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
> ```

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
```


Hide Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

