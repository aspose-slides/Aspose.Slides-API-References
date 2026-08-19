---
title: CellCollection
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili kumpulan sel.
type: docs
url: /id/com.aspose.slides/cellcollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Mewakili kumpulan sel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Mengembalikan jumlah sel dalam sebuah kumpulan. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sel berdasarkan posisinya. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi kumpulan. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh kumpulan. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari CellCollection. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari kumpulan ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah sel dalam sebuah kumpulan. Baca-saja int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Mengembalikan sel berdasarkan posisinya. Baca-saja [Cell](../../com.aspose.slides/cell).

Satu objek Cell dapat dikembalikan untuk beberapa indeks jika sel digabung.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Mengembalikan enumerator yang mengiterasi kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi kumpulan.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Mengembalikan iterator java untuk seluruh kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Sebuah java.util.Iterator untuk seluruh kumpulan.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari CellCollection. Baca-saja [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari CellCollection. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari kumpulan ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke kumpulan disinkronkan (aman terhadap thread). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object