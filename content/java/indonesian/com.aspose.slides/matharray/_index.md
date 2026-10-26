---
title: MathArray
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan array vertikal dari persamaan atau objek matematika apa pun
type: docs
url: /id/com.aspose.slides/matharray/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Menentukan array vertikal dari persamaan atau objek matematika apa pun

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getArguments()](#getArguments--) | Kumpulan item dalam array |
| [getBaseJustification()](#getBaseJustification--) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diratakan dengan bagian bawah, atas, atau tengah dari objek array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diratakan dengan bagian bawah, atas, atau tengah dari objek array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribusi Maksimum. Jika true, array didistribusikan hingga lebar maksimum elemen yang memuatnya (halaman, kolom, sel, dll.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribusi Maksimum. Jika true, array didistribusikan hingga lebar maksimum elemen yang memuatnya (halaman, kolom, sel, dll.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribusi Objek. Jika true, isi array didistribusikan hingga lebar maksimum objek array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribusi Objek. Jika true, isi array didistribusikan hingga lebar maksimum objek array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Jenis spasi vertikal antar elemen array. Default: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Jenis spasi vertikal antar elemen array. Default: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Spasi antar baris array. Hanya digunakan ketika RowSpacingRule disetel ke 3, yaitu tepat ketika satuan ukurannya adalah poin, atau Multiple ketika satuannya adalah setengah baris. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spasi antar baris array. Hanya digunakan ketika RowSpacingRule disetel ke 3, yaitu tepat ketika satuan ukurannya adalah poin, atau Multiple ketika satuannya adalah setengah baris. |
| [getChildren()](#getChildren--) | Mengambil elemen anak |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang akan ditempatkan dalam array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elemen yang akan ditempatkan dalam array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Kumpulan item dalam array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Mengembalikan:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diratakan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Mengembalikan:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diratakan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Distribusi Maksimum. Jika true, array didistribusikan hingga lebar maksimum elemen yang memuatnya (halaman, kolom, sel, dll.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Mengembalikan:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Distribusi Maksimum. Jika true, array didistribusikan hingga lebar maksimum elemen yang memuatnya (halaman, kolom, sel, dll.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Distribusi Objek. Jika true, isi array didistribusikan hingga lebar maksimum objek array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Mengembalikan:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Distribusi Objek. Jika true, isi array didistribusikan hingga lebar maksimum objek array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Jenis spasi vertikal antar elemen array. Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Mengembalikan:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Jenis spasi vertikal antar elemen array. Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Spasi antar baris array. Hanya digunakan ketika RowSpacingRule disetel ke 3, yaitu tepat ketika satuan ukurannya adalah poin, atau Multiple ketika satuannya adalah setengah baris. Default: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Mengembalikan:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Spasi antar baris array. Hanya digunakan ketika RowSpacingRule disetel ke 3, yaitu tepat ketika satuan ukurannya adalah poin, atau Multiple ketika satuannya adalah setengah baris. Default: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Mengambil elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]