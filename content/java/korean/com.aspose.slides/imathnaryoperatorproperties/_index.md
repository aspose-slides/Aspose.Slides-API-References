---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API 참조
description: IMathNaryOperator의 속성을 지정합니다
type: docs
url: /ko/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

IMathNaryOperator의 속성을 지정합니다
## 메서드

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Nary 연산자 문자 예: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary 연산자 문자 예: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 제한(첨자 및 위첨자)의 위치 |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 제한(첨자 및 위첨자)의 위치 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 연산자 문자가 피연산자 높이에 맞게 수직으로 증가합니다 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 연산자 문자가 피연산자 높이에 맞게 수직으로 증가합니다 |
| [getHideSubscript()](#getHideSubscript--) | 첨자 숨기기 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 첨자 숨기기 |
| [getHideSuperscript()](#getHideSuperscript--) | 위첨자 숨기기 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 위첨자 숨기기 |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Nary 연산자 문자 예: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**반환:**  
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

Nary 연산자 문자 예: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

제한(첨자 및 위첨자)의 위치

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**반환:**  
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

제한(첨자 및 위첨자)의 위치

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

연산자 문자가 피연산자 높이에 맞게 수직으로 증가합니다

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**반환:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

연산자 문자가 피연산자 높이에 맞게 수직으로 증가합니다

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

첨자 숨기기

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**반환:**  
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

첨자 숨기기

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

위첨자 숨기기

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**반환:**  
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

위첨자 숨기기

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |