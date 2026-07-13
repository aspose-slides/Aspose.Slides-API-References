---
title: ISequenceCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi urutan interaktif.
type: docs
url: /id/com.aspose.slides/isequencecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Mewakili koleksi urutan interaktif.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam koleksi Hanya-baca int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Menambahkan urutan interaktif baru. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Menghapus urutan yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus urutan pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua urutan dari koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan urutan pada indeks yang ditentukan. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mengembalikan jumlah elemen dalam koleksi Hanya-baca int.

**Mengembalikan:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Menambahkan urutan interaktif baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Objek Shape [IShape](../../com.aspose.slides/ishape) |

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence) - Urutan baru [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Menghapus urutan yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Urutan yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus urutan pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen dalam koleksi int |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua urutan dari koleksi.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Mengembalikan urutan pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence) - Objek [ISequence](../../com.aspose.slides/isequence).