---
title: IMathBox
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan pengemasan (boxing) logis dari elemen matematika.
type: docs
url: /id/com.aspose.slides/imathbox/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Menentukan pengemasan (boxing) logis dari elemen matematika. Sebagai contoh, objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutusan baris, atau dikelompokkan sehingga tidak mengizinkan pemutusan baris di dalamnya. Sebagai contoh, operator "==" harus dibungkus untuk mencegah pemutusan baris.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argument dasar |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator Operator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator Operator. |
| [getNoBreak()](#getNoBreak--) | Tidak ada pemutusan. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Tidak ada pemutusan. |
| [getDifferential()](#getDifferential--) | Differensial. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differensial. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Jika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditetapkan dalam persamaan lain dapat disejajarkan dengannya. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Jika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditetapkan dalam persamaan lain dapat disejajarkan dengannya. |
| [getExplicitBreak()](#getExplicitBreak--) | Pemutusan eksplisit menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris membungkus pada awal objek box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Pemutusan eksplisit menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris membungkus pada awal objek box. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument dasar

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

Operator Emulator. Jika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Operator Emulator sering digunakan ketika satu atau lebih glif digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false

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

Operator Emulator. Jika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Operator Emulator sering digunakan ketika satu atau lebih glif digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false

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

Tidak ada pemutusan. Properti ini menentukan sifat "tidak dapat diputus" pada kotak objek. Jika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Hal ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Jika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Nilai default: true

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

Tidak ada pemutusan. Properti ini menentukan sifat "tidak dapat diputus" pada kotak objek. Jika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Hal ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Jika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Nilai default: true

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

Differensial. Jika true, kotak berperan sebagai differensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk differensial matematika. Nilai default: false

--------------------

> ```
> Example:
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

Differensial. Jika true, kotak berperan sebagai differensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk differensial matematika. Nilai default: false

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

Jika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditetapkan dalam persamaan lain dapat disejajarkan dengannya. Nilai default: false

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

Jika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditetapkan dalam persamaan lain dapat disejajarkan dengannya. Nilai default: false

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

Pemutusan eksplisit menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris membungkus pada awal objek box. Menentukan nomor operator pada baris teks matematika sebelumnya yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Nilai default: 0 (tidak ada pemutusan eksplisit)

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

Pemutusan eksplisit menentukan apakah ada pemutusan baris pada awal objek Box, sehingga baris membungkus pada awal objek box. Menentukan nomor operator pada baris teks matematika sebelumnya yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Nilai default: 0 (tidak ada pemutusan eksplisit)

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