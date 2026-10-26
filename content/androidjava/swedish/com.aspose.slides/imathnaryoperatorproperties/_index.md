---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies properties of IMathNaryOperator
type: docs
url: /sv/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Specificerar egenskaper för IMathNaryOperator
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operator-tecken exempelvis: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator-tecken exempelvis: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Placeringen av gränser (nedsänkt och upphöjd) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Placeringen av gränser (nedsänkt och upphöjd) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator-tecken växer vertikalt för att matcha operandens höjd |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator-tecken växer vertikalt för att matcha operandens höjd |
| [getHideSubscript()](#getHideSubscript--) | Dölj nedsänkt |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Dölj nedsänkt |
| [getHideSuperscript()](#getHideSuperscript--) | Dölj upphöjt |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Dölj upphöjt |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary Operator-tecken exempelvis: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Returnerar:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary Operator-tecken exempelvis: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Placeringen av gränser (nedsänkt och upphöjd)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returnerar:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Placeringen av gränser (nedsänkt och upphöjd)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Operator-tecken växer vertikalt för att matcha operandens höjd

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Returnerar:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Operator-tecken växer vertikalt för att matcha operandens höjd

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Dölj nedsänkt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Returnerar:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Dölj nedsänkt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Dölj upphöjt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Returnerar:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Dölj upphöjt

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | boolean |  |