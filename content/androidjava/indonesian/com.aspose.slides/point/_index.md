---
title: Point
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili titik animasi.
type: docs
url: /id/com.aspose.slides/point/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Mewakili titik animasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Point()](#Point--) | Konstruktor default. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Membuat titik animasi dengan waktu, nilai, dan formula. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTime()](#getTime--) | Mewakili nilai waktu. |
| [setTime(float value)](#setTime-float-) | Mewakili nilai waktu. |
| [getValue()](#getValue--) | Mewakili nilai titik. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Mewakili nilai titik. |
| [getFormula()](#getFormula--) | Formula dalam nilai, atribut from, to, by dapat terdiri dari hal berikut: Operator aritmatika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) contohnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formula dalam nilai, atribut from, to, by dapat terdiri dari hal berikut: Operator aritmatika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) contohnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String. |
### Point() {#Point--}
```
public Point()
```

Konstruktor default.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Membuat titik animasi dengan waktu, nilai, dan formula.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| time | float | Nilai waktu. |
| value | java.lang.Object | Nilai titik. |
| formula | java.lang.String | Formula. |

### getTime() {#getTime--}
```
public final float getTime()
```

Mewakili nilai waktu. Baca/tulis float.

**Mengembalikan:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Mewakili nilai waktu. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Mewakili nilai titik. Hanya: bool, ColorFormat, float, int, string. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Mewakili nilai titik. Hanya: bool, ColorFormat, float, int, string. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formula dalam nilai, atribut from, to, by dapat terdiri dari hal berikut: Operator aritmatika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) contohnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formula dalam nilai, atribut from, to, by dapat terdiri dari hal berikut: Operator aritmatika standar: '+', '-', '*', '/', '^', '%' (mod) Konstanta: 'pi' 'e' Operator bersyarat: 'abs', 'min', 'max', '?' (if) Operator perbandingan: '==', '>=', '', '!=', '!' Operator trigonometri: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritma natural 'ln()' Referensi properti (properti yang didukung host) contohnya: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |