---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Java API Reference
description: Spécifie les propriétés de IMathNaryOperator
type: docs
url: /fr/com.aspose.slides/imathnaryoperatorproperties/
---
```
public interface IMathNaryOperatorProperties
```

Spécifie les propriétés de IMathNaryOperator
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Caractère de l'opérateur n-aire. Par exemple: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Caractère de l'opérateur n-aire. Par exemple: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | L'emplacement des limites (indice et exposant) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | L'emplacement des limites (indice et exposant) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande |
| [getHideSubscript()](#getHideSubscript--) | Masquer l'indice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Masquer l'indice |
| [getHideSuperscript()](#getHideSuperscript--) | Masquer l'exposant |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Masquer l'exposant |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Caractère de l'opérateur n-aire. Par exemple: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Renvoie :** 
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

Caractère de l'opérateur n-aire. Par exemple: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Paramètres :** 
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

L'emplacement des limites (indice et exposant)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Renvoie :** 
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

L'emplacement des limites (indice et exposant)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Paramètres :** 
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Renvoie :** 
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Paramètres :** 
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

Masquer l'indice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Renvoie :** 
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

Masquer l'indice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Paramètres :** 
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

Masquer l'exposant

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Renvoie :** 
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

Masquer l'exposant

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Paramètres :** 
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |