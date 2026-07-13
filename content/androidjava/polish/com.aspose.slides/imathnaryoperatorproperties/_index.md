---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies properties of IMathNaryOperator
type: docs
url: /pl/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Określa właściwości IMathNaryOperator
## Metody

| Metoda | Opis |
| --- | --- |
| [getOperator()](#getOperator--) | Znak operatora N-argumentowego Na przykład: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Znak operatora N-argumentowego Na przykład: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Lokalizacja limitów (indeks dolny i indeks górny) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Lokalizacja limitów (indeks dolny i indeks górny) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów |
| [getHideSubscript()](#getHideSubscript--) | Ukryj indeks dolny |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ukryj indeks dolny |
| [getHideSuperscript()](#getHideSuperscript--) | Ukryj indeks górny |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ukryj indeks górny |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Znak operatora N-argumentowego Na przykład: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Zwraca:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Znak operatora N-argumentowego Na przykład: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Lokalizacja limitów (indeks dolny i indeks górny)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Zwraca:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Lokalizacja limitów (indeks dolny i indeks górny)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Zwraca:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Ukryj indeks dolny

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Zwraca:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Ukryj indeks dolny

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Ukryj indeks górny

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Zwraca:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Ukryj indeks górny

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |