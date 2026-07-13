---
title: IMathMatrix
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan objek Matrix yang terdiri dari elemen anak yang disusun dalam satu atau lebih baris dan kolom.
type: docs
url: /id/com.aspose.slides/imathmatrix/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Menentukan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau beberapa baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. Untuk menempatkan matriks dalam tanda kurung Anda harus menggunakan objek delimiter (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matriks.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemen matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemen matrix |
| [getRowCount()](#getRowCount--) | Jumlah baris dalam matrix |
| [getColumnCount()](#getColumnCount--) | Jumlah kolom dalam matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Sembunyikan placeholder untuk elemen matrix kosong Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Sembunyikan placeholder untuk elemen matrix kosong Default: false |
| [getBaseJustification()](#getBaseJustification--) | Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Lebar kolom minimum dalam twips (1/20 poin) Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Lebar kolom minimum dalam twips (1/20 poin) Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). |
| [getColumnGapRule()](#getColumnGapRule--) | Jenis spasi horizontal antara kolom matrix; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Jenis spasi horizontal antara kolom matrix; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twips). |
| [getColumnGap()](#getColumnGap--) | Nilai spasi horizontal antara kolom matrix; Jika ColumnGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika ColumnGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai jumlah kenaikan 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Nilai spasi horizontal antara kolom matrix; Jika ColumnGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika ColumnGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai jumlah kenaikan 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Jenis spasi vertikal antara baris matrix; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Jenis spasi vertikal antara baris matrix; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twips). |
| [getRowGap()](#getRowGap--) | Nilai spasi vertikal antara baris matrix; Jika RowGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika RowGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai setengah baris. |
| [setRowGap(long value)](#setRowGap-long-) | Nilai spasi vertikal antara baris matrix; Jika RowGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika RowGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai setengah baris. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Dapatkan perataan horizontal kolom yang ditentukan |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Atur perataan horizontal kolom yang ditentukan |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Atur perataan horizontal kolom yang ditentukan |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Sisipkan baris baru sebelum yang ditentukan Awalnya semua elemen di baris baru adalah null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Sisipkan baris baru setelah yang ditentukan Awalnya semua elemen di baris baru adalah null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Hapus baris yang ditentukan |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Sisipkan kolom baru sebelum yang ditentukan Awalnya semua elemen di kolom baru adalah null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Sisipkan kolom baru setelah yang ditentukan Awalnya semua elemen di kolom baru adalah null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Hapus kolom yang ditentukan |
### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```


Elemen matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| row | int | Indeks berbasis nol dari baris untuk mendapatkan item |
| column | int | Indeks berbasis nol dari kolom untuk mendapatkan item |

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```


Elemen matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| row | int | Indeks berbasis nol dari baris untuk mendapatkan item |
| column | int | Indeks berbasis nol dari kolom untuk mendapatkan item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```


Jumlah baris dalam matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Mengembalikan:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Jumlah kolom dalam matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Mengembalikan:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```


Sembunyikan placeholder untuk elemen matrix kosong Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Mengembalikan:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```


Sembunyikan placeholder untuk elemen matrix kosong Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Mengembalikan:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```


Lebar kolom minimum dalam twips (1/20 poin) Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Mengembalikan:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```


Lebar kolom minimum dalam twips (1/20 poin) Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```


Jenis spasi horizontal antara kolom matrix; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Mengembalikan:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```


Jenis spasi horizontal antara kolom matrix; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```


Nilai spasi horizontal antara kolom matrix; Jika ColumnGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika ColumnGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai jumlah kenaikan 0.5 em. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Mengembalikan:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```


Nilai spasi horizontal antara kolom matrix; Jika ColumnGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika ColumnGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai jumlah kenaikan 0.5 em. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```


Jenis spasi vertikal antara baris matrix; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Mengembalikan:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```


Jenis spasi vertikal antara baris matrix; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```


Nilai spasi vertikal antara baris matrix; Jika RowGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika RowGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai setengah baris. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Mengembalikan:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```


Nilai spasi vertikal antara baris matrix; Jika RowGapRule diset ke 3 ("Exactly"), satuan dianggap sebagai twips (1/20 poin) Jika RowGapRule diset ke 4 ("Multiple"), satuan dianggap sebagai setengah baris. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```


Dapatkan perataan horizontal kolom yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks kolom berbasis nol |

**Mengembalikan:**
int - Perataan Horizontal kolom yang ditentukan
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```


Atur perataan horizontal kolom yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks kolom berbasis nol |
| val | int | Nilai baru perataan horizontal kolom yang ditentukan |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


Atur perataan horizontal kolom yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks berbasis nol dari kolom pertama untuk mengatur perataan |
| columnsCount | long | Jumlah kolom yang akan diatur perataannya |
| val | int | Nilai baru perataan horizontal kolom yang ditentukan |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```


Sisipkan baris baru sebelum yang ditentukan Awalnya semua elemen di baris baru adalah null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowIndex | int | Indeks baris sebelum mana baris baru akan disisipkan |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```


Sisipkan baris baru setelah yang ditentukan Awalnya semua elemen di baris baru adalah null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowIndex | int | Indeks baris setelah mana baris baru akan disisipkan |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```


Hapus baris yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowIndex | int | Indeks berbasis nol dari baris yang akan dihapus. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```


Sisipkan kolom baru sebelum yang ditentukan Awalnya semua elemen di kolom baru adalah null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks kolom sebelum mana kolom baru akan disisipkan |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```


Sisipkan kolom baru setelah yang ditentukan Awalnya semua elemen di kolom baru adalah null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks kolom setelah mana kolom baru akan disisipkan |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```


Hapus kolom yang ditentukan

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks berbasis nol dari kolom yang akan dihapus. |