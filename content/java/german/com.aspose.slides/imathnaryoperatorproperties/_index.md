---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides für Java API-Referenz
description: Gibt Eigenschaften von IMathNaryOperator an
type: docs
url: /de/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Gibt Eigenschaften von IMathNaryOperator an
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Der Ort der Grenzen (Tieferstellung und Hochstellung) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Der Ort der Grenzen (Tieferstellung und Hochstellung) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen |
| [getHideSubscript()](#getHideSubscript--) | Tieferstellung ausblenden |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Tieferstellung ausblenden |
| [getHideSuperscript()](#getHideSuperscript--) | Hochstellung ausblenden |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Hochstellung ausblenden |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Nary Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222b'

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

Nary Operator-Zeichen Zum Beispiel: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

Der Ort der Grenzen (Tieferstellung und Hochstellung)

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

Der Ort der Grenzen (Tieferstellung und Hochstellung)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen

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

Operator-Zeichen wächst vertikal, um die Höhe seines Operanden anzupassen

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

Tieferstellung ausblenden

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

Tieferstellung ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

Hochstellung ausblenden

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

Hochstellung ausblenden

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |