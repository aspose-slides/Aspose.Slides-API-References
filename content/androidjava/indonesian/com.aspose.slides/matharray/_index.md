---
title: MathArray
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan sebuah array vertikal berisi persamaan atau objek matematika apa pun
type: docs
url: /id/com.aspose.slides/matharray/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Menentukan sebuah array vertikal berisi persamaan atau objek matematika apa pun

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Kumpulan item dari array |
| [getBaseJustification()](#getBaseJustification--) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah sebuah objek array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah sebuah objek array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribusi Maksimum. Ketika true, array diberi jarak hingga lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribusi Maksimum. Ketika true, array diberi jarak hingga lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribusi Objek. Ketika true, konten array diberi jarak hingga lebar maksimum objek array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribusi Objek. Ketika true, konten array diberi jarak hingga lebar maksimum objek array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Jenis jarak vertikal antara elemen array. Default: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Jenis jarak vertikal antara elemen array. Default: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Jarak antar baris dalam array. Hanya digunakan ketika RowSpacingRule diatur ke 3. Jika Exactly, satuan pengukuran adalah poin; jika Multiple, satuannya adalah setengah baris. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Jarak antar baris dalam array. Hanya digunakan ketika RowSpacingRule diatur ke 3. Jika Exactly, satuan pengukuran adalah poin; jika Multiple, satuannya adalah setengah baris. |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
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
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang akan ditempatkan dalam array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Membuat array matematika dan menempatkan elemen yang ditentukan di dalamnya

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elemen yang akan ditempatkan dalam array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Kumpulan item dari array

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

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah sebuah objek array. Nilai default: Center

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

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah sebuah objek array. Nilai default: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Distribusi Maksimum. Ketika true, array diberi jarak hingga lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.).

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

Distribusi Maksimum. Ketika true, array diberi jarak hingga lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Distribusi Objek. Ketika true, konten array diberi jarak hingga lebar maksimum objek array.

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

Distribusi Objek. Ketika true, konten array diberi jarak hingga lebar maksimum objek array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Jenis jarak vertikal antara elemen array. Default: SingleLineGap

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

Jenis jarak vertikal antara elemen array. Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Jarak antar baris dalam array. Hanya digunakan ketika RowSpacingRule diatur ke 3. Jika Exactly, satuan pengukuran adalah poin; jika Multiple, satuannya adalah setengah baris. Default: 0

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

Jarak antar baris dalam array. Hanya digunakan ketika RowSpacingRule diatur ke 3. Jika Exactly, satuan pengukuran adalah poin; jika Multiple, satuannya adalah setengah baris. Default: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]