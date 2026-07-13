---
title: ColorOperationCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi operasi transformasi warna.
type: docs
url: /id/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Mewakili koleksi operasi transformasi warna.
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
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [deepClone()](#deepClone--) | Membuat salinan koleksi ColorOperationCollection. |
| [cloneT()](#cloneT--) | Menggandakan objek saat ini |

### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah operasi dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Baca/tulis [ColorOperation](../../com.aspose.slides/coloroperation).

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

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Baca/tulis [ColorOperation](../../com.aspose.slides/coloroperation).

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
| operation | int | Tipe operasi. |
| parameter | float | Parameter operasi. |

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
| operation | int | Tipe operasi. |

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
| position | int | Indeks tempat operasi akan disisipkan. |
| operation | int | Tipe operasi. |
| parameter | float | Parameter operasi. |

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
| position | int | Indeks tempat operasi akan disisipkan. |
| operation | int | Tipe operasi. |

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
| index | int | Indeks operasi warna yang akan dihapus. |

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
| array | com.aspose.ms.System.Array | Array tujuan. |
| index | int | Indeks mulai di array tujuan. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). Hanya-baca boolean.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Membuat salinan koleksi ColorOperationCollection.

**Mengembalikan:**
java.lang.Object - Baru [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) koleksi.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Menggandakan objek saat ini

**Mengembalikan:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Salinan