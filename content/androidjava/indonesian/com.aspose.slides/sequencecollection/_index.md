---
title: SequenceCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili koleksi urutan interaktif.
type: docs
url: /id/com.aspose.slides/sequencecollection/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Mewakili koleksi urutan interaktif.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam sebuah koleksi Baca-saja int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Tambahkan urutan interaktif baru. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Menghapus urutan yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus urutan pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua urutan dari koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan urutan pada indeks yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### getCount() {#getCount--}
```
public final int getCount()
```

Mengembalikan jumlah elemen dalam sebuah koleksi Baca-saja int.

**Mengembalikan:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Tambahkan urutan interaktif baru. Baca/tulis [Sequence](../../com.aspose.slides/sequence).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Menghapus urutan yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Urutan yang akan dihapus. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus urutan pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks urutan yang harus dihapus. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua urutan dari koleksi.
### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Mengembalikan urutan pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence) - Objek [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Sebuah java.util.Iterator untuk seluruh koleksi.