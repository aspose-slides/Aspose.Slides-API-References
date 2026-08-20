---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: กำหนดคุณสมบัติของ IMathNaryOperator
type: docs
url: /th/com.aspose.slides/imathnaryoperatorproperties/
---
```
public interface IMathNaryOperatorProperties
```

กำหนดคุณสมบัติของ IMathNaryOperator
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOperator()](#getOperator--) | อักขระ Nary Operator เช่น: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | อักขระ Nary Operator เช่น: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวยก) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวยก) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | อักขระ Operator เติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | อักขระ Operator เติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand |
| [getHideSubscript()](#getHideSubscript--) | ซ่อนตัวห้อย |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | ซ่อนตัวห้อย |
| [getHideSuperscript()](#getHideSuperscript--) | ซ่อนตัวยก |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | ซ่อนตัวยก |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

อักขระ Nary Operator เช่น: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**คืนค่า:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

อักขระ Nary Operator เช่น: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวยก)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**คืนค่า:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวยก)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

อักขระ Operator เติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**คืนค่า:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

อักขระ Operator เติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

ซ่อนตัวห้อย

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**คืนค่า:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

ซ่อนตัวห้อย

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

ซ่อนตัวยก

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**คืนค่า:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

ซ่อนตัวยก

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |