---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: IMathNaryOperator özelliklerini belirtir
type: docs
url: /tr/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

IMathNaryOperator özelliklerini belirtir
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOperator()](#getOperator--) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Sınırlamaların konumu (alt simge ve üst simge) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Sınırlamaların konumu (alt simge ve üst simge) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Operatör Karakteri, işlenen yüksekliğine uymak için dikey olarak büyür |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Operatör Karakteri, işlenen yüksekliğine uymak için dikey olarak büyür |
| [getHideSubscript()](#getHideSubscript--) | Alt Simgeyi Gizle |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Alt Simgeyi Gizle |
| [getHideSuperscript()](#getHideSuperscript--) | Üst Simgeyi Gizle |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Üst Simgeyi Gizle |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Döndürür:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Sınırlamaların konumu (alt simge ve üst simge)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Döndürür:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Sınırlamaların konumu (alt simge ve üst simge)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Operatör Karakteri, işlenen yüksekliğine uymak için dikey olarak büyür

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Döndürür:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Operatör Karakteri, işlenen yüksekliğine uymak için dikey olarak büyür

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Alt Simgeyi Gizle

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Döndürür:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Alt Simgeyi Gizle

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Üst Simgeyi Gizle

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Döndürür:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Üst Simgeyi Gizle

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |