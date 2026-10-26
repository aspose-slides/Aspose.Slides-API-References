---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Určuje vlastnosti rozhraní IMathNaryOperator
type: docs
url: /cs/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Určuje vlastnosti rozhraní IMathNaryOperator
## Methods

| Metoda | Popis |
| --- | --- |
| [getOperator()](#getOperator--) | Znak n-ary operátoru. Například: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Znak n-ary operátoru. Například: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Umístění limit (dolní index a horní index) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Umístění limit (dolní index a horní index) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Znak operátoru roste vertikálně tak, aby odpovídal výšce operandů |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Znak operátoru roste vertikálně tak, aby odpovídal výšce operandů |
| [getHideSubscript()](#getHideSubscript--) | Skrýt dolní index |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Skrýt dolní index |
| [getHideSuperscript()](#getHideSuperscript--) | Skrýt horní index |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Skrýt horní index |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Znak n-ary operátoru. Například: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Vrací:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Znak n-ary operátoru. Například: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Umístění limit (dolní index a horní index)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Vrací:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Umístění limit (dolní index a horní index)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Znak operátoru roste vertikálně tak, aby odpovídal výšce operandů

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Vrací:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Znak operátoru roste vertikálně tak, aby odpovídal výšce operandů

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Skrýt dolní index

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Vrací:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Skrýt dolní index

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Skrýt horní index

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Vrací:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Skrýt horní index

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |