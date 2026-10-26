---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan properti IMathNaryOperator
type: docs
url: /id/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Menentukan properti IMathNaryOperator
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOperator()](#getOperator--) | Karakter Operator Nary Contoh: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Karakter Operator Nary Contoh: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Lokasi batas (subskrip dan superskrip) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Lokasi batas (subskrip dan superskrip) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operannya |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operannya |
| [getHideSubscript()](#getHideSubscript--) | Sembunyikan Subskrip |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Sembunyikan Subskrip |
| [getHideSuperscript()](#getHideSuperscript--) | Sembunyikan Superskrip |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Sembunyikan Superskrip |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Karakter Operator Nary Contoh: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Mengembalikan:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Karakter Operator Nary Contoh: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Lokasi batas (subskrip dan superskrip)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Mengembalikan:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Lokasi batas (subskrip dan superskrip)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operannya

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Mengembalikan:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Karakter Operator tumbuh secara vertikal untuk menyesuaikan tinggi operannya

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Sembunyikan Subskrip

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Mengembalikan:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Sembunyikan Subskrip

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Sembunyikan Superskrip

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Mengembalikan:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Sembunyikan Superskrip

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |