---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Spécifie les propriétés de IMathNaryOperator
type: docs
url: /fr/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Spécifie les propriétés de IMathNaryOperator
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Caractère de l'opérateur n-aire Par exemple : '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Caractère de l'opérateur n-aire Par exemple : '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | L'emplacement des limites (indice et exposant) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | L'emplacement des limites (indice et exposant) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Le caractère de l'opérateur grandit verticalement pour correspondre à la hauteur de son opérande |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Le caractère de l'opérateur grandit verticalement pour correspondre à la hauteur de son opérande |
| [getHideSubscript()](#getHideSubscript--) | Masquer l'indice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Masquer l'indice |
| [getHideSuperscript()](#getHideSuperscript--) | Masquer l'exposant |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Masquer l'exposant |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Caractère de l'opérateur n-aire Par exemple : '\\u2211', '\\u222b'

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


Masquer l'exposant

--------------------

> ```
> Exemple :
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |