---
title: TabCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi tab.
type: docs
url: /id/com.aspose.slides/tabcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Mewakili koleksi tab.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [add(double position, int align)](#add-double-int-) | Menambahkan Tab ke koleksi. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Menambahkan Tab ke koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dari koleksi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance TabsEx sama. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [Tab](../../com.aspose.slides/tab).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Menambahkan Tab ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Mengembalikan:**
[ITab](../../com.aspose.slides/itab) - Tab yang ditambahkan.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Menambahkan Tab ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Objek Tab yang akan ditambahkan di akhir koleksi. |

**Mengembalikan:**
int - Indeks tempat tab ditambahkan.
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua elemen dari koleksi.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah dua instance TabsEx sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx yang akan dibandingkan dengan TabsEx saat ini. |

**Mengembalikan:**
boolean - **true** jika TabsEx yang ditentukan sama dengan TabsEx saat ini; selain itu, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object