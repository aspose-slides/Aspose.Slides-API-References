---
title: IMathArray
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan sebuah array vertikal berisi persamaan atau objek matematika apa pun
type: docs
url: /id/com.aspose.slides/imatharray/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Menentukan sebuah array vertikal berisi persamaan atau objek matematika apa pun

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getArguments()](#getArguments--) | Kumpulan item pada array |
| [getBaseJustification()](#getBaseJustification--) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribusi Maksimum. Ketika true, array diatur dengan lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribusi Maksimum. Ketika true, array diatur dengan lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribusi Objek. Ketika true, konten array diatur dengan lebar maksimum objek array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribusi Objek. Ketika true, konten array diatur dengan lebar maksimum objek array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Jenis spasi vertikal antara elemen array |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Jenis spasi vertikal antara elemen array |
| [getRowSpacing()](#getRowSpacing--) | Spasi antara baris dalam array. Hanya digunakan ketika RowSpacingRule disetel ke 3 Exactly, dimana satuan ukur adalah poin, atau Multiple, dimana satuan ukur adalah setengah baris. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spasi antara baris dalam array. Hanya digunakan ketika RowSpacingRule disetel ke 3 Exactly, dimana satuan ukur adalah poin, atau Multiple, dimana satuan ukur adalah setengah baris. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Kumpulan item pada array

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
public abstract int getBaseJustification()
```

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center

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
public abstract void setBaseJustification(int value)
```

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center

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
public abstract boolean getMaximumDistribution()
```

Distribusi Maksimum. Ketika true, array diatur dengan lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.).

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
public abstract void setMaximumDistribution(boolean value)
```

Distribusi Maksimum. Ketika true, array diatur dengan lebar maksimum elemen yang menampungnya (halaman, kolom, sel, dll.).

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
public abstract boolean getObjectDistribution()
```

Distribusi Objek. Ketika true, konten array diatur dengan lebar maksimum objek array.

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
public abstract void setObjectDistribution(boolean value)
```

Distribusi Objek. Ketika true, konten array diatur dengan lebar maksimum objek array.

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
public abstract int getRowSpacingRule()
```

Jenis spasi vertikal antara elemen array

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
public abstract void setRowSpacingRule(int value)
```

Jenis spasi vertikal antara elemen array

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
public abstract long getRowSpacing()
```

Spasi antara baris dalam array. Hanya digunakan ketika RowSpacingRule disetel ke 3 Exactly, dimana satuan ukur adalah poin, atau Multiple, dimana satuan ukur adalah setengah baris. Nilai default: 0

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
public abstract void setRowSpacing(long value)
```

Spasi antara baris dalam array. Hanya digunakan ketika RowSpacingRule disetel ke 3 Exactly, dimana satuan ukur adalah poin, atau Multiple, dimana satuan ukur adalah setengah baris. Nilai default: 0

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