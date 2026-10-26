---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides für Android via Java API-Referenz
description: Gibt die Eigenschaften von IMathNaryOperator an
type: docs
url: /de/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Gibt die Eigenschaften von IMathNaryOperator an
## Methoden

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Nary-Operatorzeichen zum Beispiel: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary-Operatorzeichen zum Beispiel: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Der Ort der Grenzen (tiefgestellte und hochgestellte) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Der Ort der Grenzen (tiefgestellte und hochgestellte) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen |
| [getHideSubscript()](#getHideSubscript--) | Subscript ausblenden |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Subscript ausblenden |
| [getHideSuperscript()](#getHideSuperscript--) | Superscript ausblenden |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Superscript ausblenden |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary-Operatorzeichen zum Beispiel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Rückgabewert:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary-Operatorzeichen zum Beispiel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Der Ort der Grenzen (tiefgestellte und hochgestellte)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Rückgabewert:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Der Ort der Grenzen (tiefgestellte und hochgestellte)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Rückgabewert:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Operatorzeichen wächst vertikal, um die Höhe des Operanden anzupassen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Subscript ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Rückgabewert:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Subscript ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Superscript ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Rückgabewert:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Superscript ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |