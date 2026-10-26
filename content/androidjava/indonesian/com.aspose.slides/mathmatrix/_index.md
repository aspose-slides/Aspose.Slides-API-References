---
title: MathMatrix
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menentukan objek Matrix yang terdiri dari elemen anak yang disusun dalam satu atau beberapa baris dan kolom.
type: docs
url: /id/com.aspose.slides/mathmatrix/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Menentukan objek Matrix, yang terdiri dari elemen anak yang disusun dalam satu atau beberapa baris dan kolom. Penting untuk dicatat bahwa matriks tidak memiliki pembatas bawaan. Untuk menempatkan matriks di dalam kurung, Anda harus menggunakan objek pembatas (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matriks.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Menginisialisasi instance baru dari kelas MathMatrix. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRowCount()](#getRowCount--) | Jumlah baris dalam matriks |
| [getColumnCount()](#getColumnCount--) | Jumlah kolom dalam matriks |
| [getHidePlaceholders()](#getHidePlaceholders--) | Sembunyikan ruang penampung untuk elemen matriks kosong Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Sembunyikan ruang penampung untuk elemen matriks kosong Default: false |
| [getBaseJustification()](#getBaseJustification--) | Menentukan perataan vertikal terhadap teks sekitarnya |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan perataan vertikal terhadap teks sekitarnya |
| [getMinColumnWidth()](#getMinColumnWidth--) | Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). |
| [getColumnGapRule()](#getColumnGapRule--) | Jenis spasi horizontal antara kolom matriks; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twip). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Jenis spasi horizontal antara kolom matriks; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twip). |
| [getColumnGap()](#getColumnGap--) | Nilai spasi horizontal antara kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Nilai spasi horizontal antara kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Jenis spasi vertikal antara baris matriks; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twip). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Jenis spasi vertikal antara baris matriks; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twip). |
| [getRowGap()](#getRowGap--) | Nilai spasi vertikal antara baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. |
| [setRowGap(long value)](#setRowGap-long-) | Nilai spasi vertikal antara baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemen matriks |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemen matriks |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Dapatkan perataan horizontal kolom yang ditentukan |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Atur perataan horizontal kolom yang ditentukan |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Atur perataan horizontal kolom yang ditentukan |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Sisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen di baris baru adalah null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Sisipkan baris baru setelah yang ditentukan. Awalnya semua elemen di baris baru adalah null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Menghapus baris yang ditentukan |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Sisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen di kolom baru adalah null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Sisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen di kolom baru adalah null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Menghapus kolom yang ditentukan |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Menginisialisasi instance baru dari kelas MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowCount | int | jumlah baris |
| columnCount | int | jumlah kolom |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Jumlah baris dalam matriks

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
public final int getColumnCount()
```

Jumlah kolom dalam matriks

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
public final boolean getHidePlaceholders()
```

Sembunyikan ruang penampung untuk elemen matriks kosong Default: false

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
public final void setHidePlaceholders(boolean value)
```

Sembunyikan ruang penampung untuk elemen matriks kosong Default: false

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
public final int getBaseJustification()
```

Menentukan perataan vertikal terhadap teks sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center

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
public final void setBaseJustification(int value)
```

Menentukan perataan vertikal terhadap teks sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center

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
public final long getMinColumnWidth()
```

Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

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
public final void setMinColumnWidth(long value)
```

Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Jarak Kolom Matriks (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

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
public final int getColumnGapRule()
```

Jenis spasi horizontal antara kolom matriks; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twip). Default: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

Jenis spasi horizontal antara kolom matriks; satuan spasi horizontal dapat berupa ems atau poin (disimpan sebagai twip). Default: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Nilai spasi horizontal antara kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. Dalam kasus lain diabaikan. Default: 0

--------------------

> ```
> Contoh:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Mengembalikan:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Nilai spasi horizontal antara kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. Dalam kasus lain diabaikan. Default: 0

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
public final int getRowGapRule()
```

Jenis spasi vertikal antara baris matriks; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twip). Default: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

Jenis spasi vertikal antara baris matriks; satuan spasi vertikal dapat berupa baris atau poin (disimpan sebagai twip). Default: SingleSpacingGap (0)

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
public final long getRowGap()
```

Nilai spasi vertikal antara baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. Default: 0

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
public final void setRowGap(long value)
```

Nilai spasi vertikal antara baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. Default: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Elemen matriks

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
| row | int | Indeks berbasis nol dari baris untuk mengambil item |
| column | int | Indeks berbasis nol dari kolom untuk mengambil item |

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Elemen matriks

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
| row | int | Indeks berbasis nol dari baris untuk mengambil item |
| column | int | Indeks berbasis nol dari kolom untuk mengambil item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
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
public final void setColumnAlignment(int columnIndex, int val)
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
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Atur perataan horizontal kolom yang ditentukan

--------------------

> ```
> Example  



```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks berbasis nol dari kolom pertama untuk mengatur perataan |
| columnsCount | long | Jumlah kolom untuk menentukan perataan |
| val | int | Nilai baru perataan horizontal kolom yang ditentukan |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Sisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen di baris baru adalah null.

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
public final void insertRowAfter(int rowIndex)
```

Sisipkan baris baru setelah yang ditentukan. Awalnya semua elemen di baris baru adalah null.

--------------------

> ```
> Contoh:
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
public final void deleteRow(int rowIndex)
```

Menghapus baris yang ditentukan

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
public final void insertColumnBefore(int columnIndex)
```

Sisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen di kolom baru adalah null.

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
public final void insertColumnAfter(int columnIndex)
```

Sisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen di kolom baru adalah null.

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
public final void deleteColumn(int columnIndex)
```

Menghapus kolom yang ditentukan

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]