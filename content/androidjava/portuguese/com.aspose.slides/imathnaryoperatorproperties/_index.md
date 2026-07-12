---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica propriedades de IMathNaryOperator
type: docs
url: /pt/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Especifica propriedades de IMathNaryOperator
## Métodos

| Método | Descrição |
| --- | --- |
| [getOperator()](#getOperator--) | Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | A localização dos limites (subscrito e sobrescrito) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | A localização dos limites (subscrito e sobrescrito) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | O caractere do operador cresce verticalmente para corresponder à altura do operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | O caractere do operador cresce verticalmente para corresponder à altura do operando |
| [getHideSubscript()](#getHideSubscript--) | Ocultar Subscrito |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ocultar Subscrito |
| [getHideSuperscript()](#getHideSuperscript--) | Ocultar Sobrescrito |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ocultar Sobrescrito |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Retorna:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


A localização dos limites (subscrito e sobrescrito)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**Retorna:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


A localização dos limites (subscrito e sobrescrito)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


O caractere do operador cresce verticalmente para corresponder à altura do operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```


**Retorna:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


O caractere do operador cresce verticalmente para corresponder à altura do operando

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Ocultar Subscrito

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```


**Retorna:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Ocultar Subscrito

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Ocultar Sobrescrito

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```


**Retorna:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Ocultar Sobrescrito

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |