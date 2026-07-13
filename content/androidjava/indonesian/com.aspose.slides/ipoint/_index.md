---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /id/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Represent animation point.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTime()](#getTime--) | Mewakili nilai waktu. |
| [setTime(float value)](#setTime-float-) | Mewakili nilai waktu. |
| [getValue()](#getValue--) | Mewakili nilai titik. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Mewakili nilai titik. |
| [getFormula()](#getFormula--) | Formula dalam nilai, atribut from, to, by dapat dibuat dari: Operator aritmetika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) misalnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formula dalam nilai, atribut from, to, by dapat dibuat dari: Operator aritmetika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) misalnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```


Mewakili nilai waktu. Baca/tulis float.

**Mengembalikan:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```


Mewakili nilai waktu. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Mewakili nilai titik. Hanya: bool, ColorFormat, float, int, string. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Mewakili nilai titik. Hanya: bool, ColorFormat, float, int, string. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Formula dalam nilai, atribut from, to, by dapat dibuat dari: Operator aritmetika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) misalnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Formula dalam nilai, atribut from, to, by dapat dibuat dari: Operator aritmetika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) misalnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |