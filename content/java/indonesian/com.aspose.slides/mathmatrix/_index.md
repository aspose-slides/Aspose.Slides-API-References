---
title: MathMatrix
second_title: Referensi API Aspose.Slides untuk Java
description: Menyatakan objek Matrix yang terdiri dari elemen anak yang diatur dalam satu atau beberapa baris dan kolom.
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

Menyatakan objek Matrix, yang terdiri dari elemen anak yang diatur dalam satu atau beberapa baris dan kolom. Penting untuk dicatat bahwa matrix tidak memiliki delimiter bawaan. Untuk menempatkan matrix dalam kurung, Anda harus menggunakan objek delimiter (IMathDelimiter). Argumen null dapat digunakan untuk membuat celah dalam matrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Constructors

| Konstruktor | Deskripsi |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inisialisasi instance baru dari kelas MathMatrix. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRowCount()](#getRowCount--) | Jumlah baris dalam matrix |
| [getColumnCount()](#getColumnCount--) | Jumlah kolom dalam matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Menyembunyikan placeholder untuk elemen matrix kosong Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Menyembunyikan placeholder untuk elemen matrix kosong Default: false |
| [getBaseJustification()](#getBaseJustification--) | Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Spasi Kolom Matrix (jarak antara tepi yang sama dari kolom yang berbeda). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Spasi Kolom Matrix (jarak antara tepi yang sama dari kolom yang berbeda). |
| [getColumnGapRule()](#getColumnGapRule--) | Jenis spasi horizontal antara kolom dalam matrix; satuan spasi horizontal dapat berupa em atau poin (disimpan sebagai twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Jenis spasi horizontal antara kolom dalam matrix; satuan spasi horizontal dapat berupa em atau poin (disimpan sebagai twips). |
| [getColumnGap()](#getColumnGap--) | Nilai spasi horizontal antara kolom dalam matrix; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | Nilai spasi horizontal antara kolom dalam matrix; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0 |
| [getRowGapRule()](#getRowGapRule--) | Jenis spasi vertikal antara baris dalam matrix; satuan spasi vertikal dapat berupa garis atau poin (disimpan sebagai twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Jenis spasi vertikal antara baris dalam matrix; satuan spasi vertikal dapat berupa garis atau poin (disimpan sebagai twips). |
| [getRowGap()](#getRowGap--) | Nilai spasi vertikal antara baris dalam matrix; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai setengah garis. Default: 0 |
| [setRowGap(long value)](#setRowGap-long-) | Nilai spasi vertikal antara baris dalam matrix; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai setengah garis. Default: 0 |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemen matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemen matrix |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Dapatkan perataan horizontal kolom yang ditentukan |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Setel perataan horizontal kolom yang ditentukan |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Setel perataan horizontal kolom yang ditentukan |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Sisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen dalam baris baru bernilai null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Sisipkan baris baru setelah yang ditentukan. Awalnya semua elemen dalam baris baru bernilai null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Menghapus baris yang ditentukan |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Sisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen dalam kolom baru bernilai null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Sisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen dalam kolom baru bernilai null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Menghapus kolom yang ditentukan |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inisialisasi instance baru dari kelas MathMatrix.

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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Menyembunyikan placeholder untuk elemen matrix kosong Default: false

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

Menyembunyikan placeholder untuk elemen matrix kosong Default: false

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

Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. Nilai yang memungkinkan: top, bottom, dan center. Default: Center

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

Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. Nilai yang memungkinkan: top, bottom, dan center. Default: Center

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

Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Spasi Kolom Matrix (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

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

Lebar minimum kolom dalam twips (1/20 poin). Jarak celah (juga disebut \\u201cColumn Gap\\u201d atau \\u201cGap Width\\u201d) ditambahkan ke MinColumnWidth untuk menentukan total Spasi Kolom Matrix (jarak antara tepi yang sama dari kolom yang berbeda). Default: 0.

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

Jenis spasi horizontal antara kolom dalam matrix; satuan spasi horizontal dapat berupa em atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

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

Jenis spasi horizontal antara kolom dalam matrix; satuan spasi horizontal dapat berupa em atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

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

Nilai spasi horizontal antara kolom dalam matrix; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0

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
public final void setColumnGap(long value)
```

Nilai spasi horizontal antara kolom dalam matrix; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0

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

Jenis spasi vertikal antara baris dalam matrix; satuan spasi vertikal dapat berupa garis atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

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

Jenis spasi vertikal antara baris dalam matrix; satuan spasi vertikal dapat berupa garis atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

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

Nilai spasi vertikal antara baris dalam matrix; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai setengah garis. Default: 0

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

Nilai spasi vertikal antara baris dalam matrix; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin). Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai setengah garis. Default: 0

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
public final void set_Item(int row, int column, IMathElement value)
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

Setel perataan horizontal kolom yang ditentukan

--------------------

> ```
> Example



```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int | Indeks kolom berbasis nol |
| val | int | Nilai baru perataan horizontal kolom yang ditentukan |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Setel perataan horizontal kolom yang ditentukan

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
| columnIndex | int | Indeks berbasis nol kolom pertama untuk menyetel perataan |
| columnsCount | long | Jumlah kolom yang akan ditetapkan perataannya |
| val | int | Nilai baru perataan horizontal kolom yang ditentukan |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Sisipkan baris baru sebelum yang ditentukan. Awalnya semua elemen dalam baris baru bernilai null.

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

Sisipkan baris baru setelah yang ditentukan. Awalnya semua elemen dalam baris baru bernilai null.

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

Sisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen dalam kolom baru bernilai null.

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

Sisipkan kolom baru setelah yang ditentukan. Awalnya semua elemen dalam kolom baru bernilai null.

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