---
title: ColorOperationCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekumpulan operasi transformasi warna.
type: docs
url: /id/com.aspose.slides/coloroperationcollection/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Mewakili sekumpulan operasi transformasi warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah operasi dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan atau mengatur operasi pada indeks yang ditentukan. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Mengembalikan atau mengatur operasi pada indeks yang ditentukan. |
| [add(int operation, float parameter)](#add-int-float-) | Menambahkan operasi baru ke akhir koleksi. |
| [add(int operation)](#add-int-) | Menambahkan operasi baru ke akhir koleksi. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Menyisipkan operasi baru ke dalam koleksi. |
| [insert(int position, int operation)](#insert-int-int-) | Menyisipkan operasi baru ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus operasi warna dari koleksi. |
| [clear()](#clear--) | Menghapus semua operasi warna. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [deepClone()](#deepClone--) | Membuat salinan koleksi ColorOperationCollection. |
| [cloneT()](#cloneT--) | Mengkloning objek saat ini |
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah operasi dalam koleksi. Read-only int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Menambahkan operasi baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang ditambahkan.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Menambahkan operasi baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operation | int | Operation type. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang ditambahkan.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Menyisipkan operasi baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang disisipkan.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Menyisipkan operasi baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang disisipkan.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus operasi warna dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Index of a color operation to remove. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua operasi warna.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Read-only boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Read-only Object.

**Mengembalikan:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Membuat salinan koleksi ColorOperationCollection.

**Mengembalikan:**
java.lang.Object - Koleksi [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) baru.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Mengkloning objek saat ini

**Mengembalikan:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clone