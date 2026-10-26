---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides per Java Riferimento API
description: Specifica le proprietà di IMathNaryOperator
type: docs
url: /it/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Specifica le proprietà di IMathNaryOperator
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOperator()](#getOperator--) | Carattere dell'operatore Nario Ad esempio: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Carattere dell'operatore Nario Ad esempio: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | La posizione dei limiti (pedice e apice) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | La posizione dei limiti (pedice e apice) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando |
| [getHideSubscript()](#getHideSubscript--) | Nascondi pedice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Nascondi pedice |
| [getHideSuperscript()](#getHideSuperscript--) | Nascondi apice |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Nascondi apice |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Carattere dell'operatore Nario Ad esempio: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Restituisce:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

Carattere dell'operatore Nario Ad esempio: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |
### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

La posizione dei limiti (pedice e apice)

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Restituisce:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

La posizione dei limiti (pedice e apice)

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Restituisce:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

Nascondi pedice

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Restituisce:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

Nascondi pedice

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

Nascondi apice

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Restituisce:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

Nascondi apice

--------------------

> ```
> Esempio:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |