---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: Specificeert eigenschappen van IMathNaryOperator
type: docs
url: /nl/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Specificeert eigenschappen van IMathNaryOperator
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operator-teken Bijvoorbeeld: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator-teken Bijvoorbeeld: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | De locatie van limieten (subscript en superscript) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | De locatie van limieten (subscript en superscript) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator-teken groeit verticaal om zijn operandhoogte te evenaren |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator-teken groeit verticaal om zijn operandhoogte te evenaren |
| [getHideSubscript()](#getHideSubscript--) | Verberg Subscript |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Verberg Subscript |
| [getHideSuperscript()](#getHideSuperscript--) | Verberg Superscript |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Verberg Superscript |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary Operator-teken Bijvoorbeeld: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Retour:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary Operator-teken Bijvoorbeeld: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


De locatie van limieten (subscript en superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Retour:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


De locatie van limieten (subscript en superscript)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Operator-teken groeit verticaal om zijn operandhoogte te evenaren

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Retour:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Operator-teken groeit verticaal om zijn operandhoogte te evenaren

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Verberg Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Retour:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Verberg Subscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Verberg Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Retour:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Verberg Superscript

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |