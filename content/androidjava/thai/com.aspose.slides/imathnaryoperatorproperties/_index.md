---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies properties of IMathNaryOperator
type: docs
url: /th/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

ระบุคุณสมบัติของ IMathNaryOperator
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOperator()](#getOperator--) | อักขระ Nary Operator ตัวอย่างเช่น '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | อักขระ Nary Operator ตัวอย่างเช่น '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวสูง) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวสูง) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | อักขระ Operator เติบโตแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | อักขระ Operator เติบโตแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์ |
| [getHideSubscript()](#getHideSubscript--) | ซ่อนตัวห้อย |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | ซ่อนตัวห้อย |
| [getHideSuperscript()](#getHideSuperscript--) | ซ่อนตัวสูง |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | ซ่อนตัวสูง |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

อักขระ Nary Operator ตัวอย่างเช่น '\\u2211', '\\u222b'

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

อักขระ Nary Operator ตัวอย่างเช่น '\\u2211', '\\u222b'

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

ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวสูง)

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

ตำแหน่งของขีดจำกัด (ตัวห้อยและตัวสูง)

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

อักขระ Operator เติบโตแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์

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

อักขระ Operator เติบโตแนวตั้งเพื่อให้ตรงกับความสูงของโอเปอแรนด์

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

ซ่อนตัวสูง

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

ซ่อนตัวสูง

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