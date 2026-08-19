---
title: IMathBox
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan pengemasan (boxing) logis elemen matematika.
type: docs
url: /id/com.aspose.slides/imathbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Spesifikasi pengemasan (boxing) logis elemen matematika. Misalnya, objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik perataan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. Contohnya, operator "==" harus dibungkus untuk mencegah pemutusan baris.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator Operator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator Operator. |
| [getNoBreak()](#getNoBreak--) | Tidak ada jeda. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Tidak ada jeda. |
| [getDifferential()](#getDifferential--) | Diferensial. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferensial. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Saat true, emulator operator ini berfungsi sebagai titik perataan; yaitu, titik perataan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Saat true, emulator operator ini berfungsi sebagai titik perataan; yaitu, titik perataan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. |
| [getExplicitBreak()](#getExplicitBreak--) | Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumen dasar

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```


Emulator Operator. Saat true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti operator. Ini berarti, misalnya, karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph bergabung membentuk sebuah operator, seperti '=='. Nilai default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Mengembalikan:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```


Emulator Operator. Saat true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti operator. Ini berarti, misalnya, karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph bergabung membentuk sebuah operator, seperti '=='. Nilai default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


Tidak ada jeda. Properti ini menentukan properti "tidak dapat diputus" pada kotak objek. Saat true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Mengembalikan:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```


Tidak ada jeda. Properti ini menentukan properti "tidak dapat diputus" pada kotak objek. Saat true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


Diferensial. Saat true, kotak berfungsi sebagai diferensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima jarak horizontal yang sesuai untuk diferensial matematika. Nilai default: false

--------------------

> ```
> Contoh:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Mengembalikan:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```


Diferensial. Saat true, kotak berfungsi sebagai diferensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima jarak horizontal yang sesuai untuk diferensial matematika. Nilai default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


Saat true, emulator operator ini berfungsi sebagai titik perataan; yaitu, titik perataan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. Nilai default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Mengembalikan:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```


Saat true, emulator operator ini berfungsi sebagai titik perataan; yaitu, titik perataan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. Nilai default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris teks matematika sebelumnya yang akan digunakan sebagai titik perataan untuk baris teks matematika saat ini. Nilai yang memungkinkan: 1..255 Nilai default: 0 (tidak ada pemutusan eksplisit)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Mengembalikan:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```


Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris teks matematika sebelumnya yang akan digunakan sebagai titik perataan untuk baris teks matematika saat ini. Nilai yang memungkinkan: 1..255 Nilai default: 0 (tidak ada pemutusan eksplisit)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |