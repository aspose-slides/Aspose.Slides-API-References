---
title: SectionSlideCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi slide dalam bagian.
type: docs
url: /id/com.aspose.slides/sectionslidecollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Mewakili kumpulan slide dalam bagian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin seluruh koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target |
| index | int | Indeks dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Sebuah java.util.Iterator untuk seluruh koleksi.