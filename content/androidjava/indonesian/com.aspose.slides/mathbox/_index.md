---
title: MathBox
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan pengemasan logis kotak elemen matematika.
type: docs
url: /id/com.aspose.slides/mathbox/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Menentukan pengemasan logis (packaging) elemen matematis. Misalnya, sebuah objek yang dibungkus dapat berfungsi sebagai emulator operator dengan atau tanpa titik penyelarasan, berfungsi sebagai titik pemutus baris, atau dikelompokkan sehingga tidak memperbolehkan pemutusan baris di dalamnya. Misalnya, operator "==" harus dibungkus untuk mencegah pemutusan baris.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Menginisialisasi MathBox dengan elemen yang ditentukan sebagai argumen |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen dasar |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulator Operator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulator Operator. |
| [getNoBreak()](#getNoBreak--) | Tidak terputus Properti ini menentukan properti "tidak dapat dipatahkan" pada kotak objek. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Tidak terputus Properti ini menentukan properti "tidak dapat dipatahkan" pada kotak objek. |
| [getDifferential()](#getDifferential--) | Diferensial Ketika true, kotak berperilaku sebagai diferensial (misalnya, \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferensial Ketika true, kotak berperilaku sebagai diferensial (misalnya, \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Ketika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Ketika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. |
| [getExplicitBreak()](#getExplicitBreak--) | Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Menginisialisasi MathBox dengan elemen yang ditentukan sebagai argumen

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen dasar yang diterapkan pada kotak. Dapat bernilai null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumen dasar

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Emulator Operator. Ketika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glif digabungkan membentuk sebuah operator, seperti '=='. Nilai default: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Mengembalikan:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Emulator Operator. Ketika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glif digabungkan membentuk sebuah operator, seperti '=='. Nilai default: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Tidak terputus Properti ini menentukan properti "tidak dapat dipatahkan" pada kotak objek. Ketika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Mengembalikan:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Tidak terputus Properti ini menentukan properti "tidak dapat dipatahkan" pada kotak objek. Ketika true, tidak ada pemutusan baris yang dapat terjadi di dalam kotak. Ini dapat penting untuk emulator operator yang terdiri dari lebih dari satu operator biner. Ketika elemen ini tidak ditentukan, pemutusan dapat terjadi di dalam kotak. Default: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Diferensial Ketika true, kotak berperilaku sebagai diferensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false

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
public final void setDifferential(boolean value)
```


Diferensial Ketika true, kotak berperilaku sebagai diferensial (mis., \\ud835\\udc51\\ud835\\udc65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false

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
public final boolean getAlignmentPoint()
```


Ketika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. Default: false

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
public final void setAlignmentPoint(boolean value)
```


Ketika true, emulator operator ini berfungsi sebagai titik penyelarasan; yaitu, titik penyelarasan yang ditentukan dalam persamaan lain dapat disejajarkan dengannya. Default: false

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
public final byte getExplicitBreak()
```


Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit)

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
public final void setExplicitBreak(byte value)
```


Pemutusan eksplisit menentukan apakah ada pemutusan baris di awal objek Box, sehingga baris membungkus di awal objek box. Menentukan nomor operator pada baris sebelumnya dari teks matematika yang akan digunakan sebagai titik penyelarasan untuk baris teks matematika saat ini. Nilai yang mungkin: 1..255 Default: 0 (tidak ada pemutusan eksplisit)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Mendapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps