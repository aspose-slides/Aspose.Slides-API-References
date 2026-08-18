---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: Specifies properties of IMathNaryOperator
type: docs
url: /es/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Especifica las propiedades de IMathNaryOperator
## Métodos

| Método | Descripción |
| --- | --- |
| [getOperator()](#getOperator--) | Carácter del operador nario Por ejemplo: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Carácter del operador nario Por ejemplo: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | La ubicación de los límites (subíndice y superíndice) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | La ubicación de los límites (subíndice y superíndice) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | El carácter del operador crece verticalmente para coincidir con la altura de su operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | El carácter del operador crece verticalmente para coincidir con la altura de su operando |
| [getHideSubscript()](#getHideSubscript--) | Ocultar subíndice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ocultar subíndice |
| [getHideSuperscript()](#getHideSuperscript--) | Ocultar superíndice |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ocultar superíndice |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Carácter del operador nario Por ejemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Devuelve:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Carácter del operador nario Por ejemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


La ubicación de los límites (subíndice y superíndice)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Devuelve:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


La ubicación de los límites (subíndice y superíndice)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


El carácter del operador crece verticalmente para coincidir con la altura de su operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Devuelve:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


El carácter del operador crece verticalmente para coincidir con la altura de su operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Ocultar subíndice

--------------------

> ```
> Example:
>  
  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Devuelve:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Ocultar subíndice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Ocultar superíndice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Devuelve:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Ocultar superíndice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |